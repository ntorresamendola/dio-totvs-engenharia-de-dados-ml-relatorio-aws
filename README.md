# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 16/05/2026

Empresa: Abstergo Industries

Responsável: Natanael T. A.

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries , realizado por Natanael T. A. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

- Serviço: Amazon Web Services Identity and Access Management (IAM)
- Foco da ferramenta: controlar autenticação e autorização.
- Por que usar nesta etapa: Primeiro é necessário controlar e identificar quem acessa cada recurso da nuvem. Criar usuários, grupos e permissões para times de TI, logística, qualidade, controle de estoque, financeiro, RH e todos os outros. Embora não tenha um impacto inicial imediato nas finanças, ter o IAM bem configurado e usando as melhores práticas de segurança (princípio do menor privilégio, autenticação de dois fatores) trará benefícios financeiros ao longo prazo, ao tornar a implementação e manutenção das próximas etapas menos custosa, reduzir a possibilidade de erros e falhas no sistema, sejam elas causadas por descuido ou por ações maliciosas, e garantirá a segurança dos dados e operações da empresa, além de reduzir a necessidade de termos uma equipe tão grande dedicada a cibersegurança.
- Caso de uso: separar o acesso entre operadores de estoque, gestores de distribuição, administradores, especialistas farmacêuticos, recursos humanos e todos os outros setores da empresa. Garantir que dados sigilosos só possam ser acessados por um grupo seleto de pessoas e que operações que requerem especial segurança, como a compra e venda de medicamentos de uso controlado, tenham a autorização das pessoas certas e sigam corretamente os protocolos.

Etapa 2:

- Serviço: Amazon Simple Storage Service (S3)
- Foco da ferramenta: armazenamento de dados durável e altamente centralizado, com controle de acesso e versionamento de dados.
- Por que usar nesta etapa: os dados são a base do serviço em nuvem. É necessário antes de tudo ter um armazenamento persistente e confiável para armazenar nossos documentos e bases de dado. Usar o S3 iria reduzir os nossos custos de infraestrutura, pois não teríamos que lidar nós mesmos não só com o armazenamento de dados, o que gera um custo alto de compra e manutenção de hardware, mas também garantir sua segurança, disponibilidade e seus backups, o que requer um time dedicado especializado. É recomendado usar o S3 Intelligent-tiering, que ajusta a categoria do dado e o preço pago pelo armazenamento automaticamente conforme o uso, o que otimiza os custos e o desempenho.
- Caso de uso: guardar documentos regulatórios, XMS fiscais, notas e comprovantes, certificados de qualidade, inventário, arquivo de comprovantes de entrega, backups, rastreabilidade por lote, versionamento e retenção de documentos, armazenamento de logs.

Etapa 3:

- Serviço: Amazon Relational Database Service (RDS)
- Banco de dados relacional gerenciado que conta com patches automatizados, backups e redundância.
- Por que usar nesta etapa: tendo os dados brutos já sido armazenáveis na etapa 2, organizar e acessar dados estruturados é a medida que mais geraria economia para a empresa. Gerenciar nossa própria estrutura de banco de dados, desde o armazenamento físico em hardware até as autorizações de operações, requer um time especializado em banco de dados, segurança e infraestrutura, funções especializadas que oneram de forma significativa a folha de pagamento da nossa empresa.
- Caso de uso: armazenar e consultar bases de clientes, fornecedores, catálogos de produtos, pedidos, estoque por lote/validade, histórico de movimentação, informações sobre colaboradores e tantos outros dados que precisam ser armazenados e acessados na operação da nossa empresa.

## Conclusão

A implementação de ferramentas na empresa * Abstergo Industries tem como esperado a redução de custos com a manutenção, operação e segurança dos dados da empresa, diminuindo a necessidade de colaboradores dedicados e especialistas, assim como a compra e manutenção de hardware e software dedicados *, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

Sobre o AWS IAM: [AWS IAM](https://docs.aws.amazon.com/pt_br/iam/)

Sobre o Amazon Simple Storage Service: [AWS S3](https://aws.amazon.com/pt/s3/)

Sobre o Amazon Relational Database Service: [AWS RDS](https://aws.amazon.com/pt/rds/)

Assinatura do Responsável pelo Projeto:

Natanael T. A.
