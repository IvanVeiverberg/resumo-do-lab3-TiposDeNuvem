# Tipos de Serviço de Nuvem na Azure
---
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab Tipos de Serviço de Nuvem na plataforma DIO

---
## Introdução

Neste laboratório foram apresentados os serviços de nuvem da Azure, os quais são classificados em três principais modelos: IaaS, PaaS e SaaS, cada um com diferentes níveis de controle e responsabilidades para o cliente e o provedor. Com esses modelos, as empresas podem escolher a abordagem que melhor se adapta às suas necessidades de desenvolvimento, gerenciamento e operação, aproveitando a flexibilidade e a escalabilidade oferecidas pela plataforma.

---

## IaaS (Infrastructure as a Service)
- Oferece maior controle e flexibilidade ao cliente, que é responsável pela configuração, monitoramento, backup e gestão dos recursos.
- Permite personalização de recursos, com o cliente assumindo responsabilidade sobre informações, dispositivos, contas, identidades, infraestrutura de diretório, aplicativos, controles de rede e o sistema operacional.
- A Microsoft é responsável pelos hosts, redes e datacenters.
- Exemplo: Criação de máquinas virtuais, onde o cliente pode escolher imagens, arquitetura, adicionar discos e definir a exposição à internet e proteção.

## PaaS (Platform as a Service)
- Focado em desenvolvimento, teste e implantação de aplicativos sem a necessidade de gerenciar a infraestrutura subjacente.
- Oferece um ambiente de desenvolvimento completo com sistemas operacionais, ferramentas de desenvolvimento, análise de negócios e gerenciamento de banco de dados.
- Responsabilidade compartilhada: a Microsoft cuida dos hosts, redes, datacenters e sistemas operacionais, enquanto o cliente é responsável por informações, dispositivos, contas e identidade.
- Algumas responsabilidades, como infraestrutura de diretório e controle de rede, são compartilhadas entre a Microsoft e o cliente.

## SaaS (Software as a Service)
- Modelo de pagamento conforme o uso, onde os clientes têm menor controle sobre a infraestrutura e maior conveniência no uso de aplicativos prontos.
- A Microsoft gerencia todos os aspectos, incluindo hosts, redes, datacenters, sistemas operacionais, aplicativos e controles de rede.
- O cliente é responsável apenas por informações, dispositivos, contas e identidade.
- Exemplo: Aplicações como MS Teams, Office 365, e-mail e calendários, onde o acesso e a funcionalidade dependem do nível de licenciamento adquirido.

---

# Tipos de Nuvem - Laboratório

## Criação de Máquinas Virtuais
- Escolha de imagens e arquitetura, como Windows Server 2019 Datacenter (x64 Gen2).
- Definição de tamanho da máquina com custo por mês.
- Possibilidade de adicionar discos além dos padrões e definir se a máquina será exposta à internet.
- Configuração de proteção de gerenciamento e opções de desligamento automático.

## Criação de Banco de Dados
- Criação de banco de dados SQL com a necessidade de um servidor.
- A calculadora de custos é útil para definir recursos e gerar um relatório detalhado para o cliente.

## Considerações Gerais
- Quanto mais o cliente estiver envolvido na gestão dos recursos, menor será a responsabilidade da Microsoft e vice-versa.
- A infraestrutura como serviço (IaaS) demanda mais ajustes e manutenção pelo cliente, enquanto os modelos PaaS e SaaS têm menos envolvimento na gestão direta.
