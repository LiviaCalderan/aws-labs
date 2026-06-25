# AWS Labs

Repositório criado para documentar meus laboratórios, práticas e aprendizados durante meus estudos em cloud computing, com foco na AWS e na preparação para as certificações:

- AWS Certified Developer - Associate
- AWS Certified Solutions Architect - Associate

A ideia deste espaço é registrar, de forma prática e organizada, os serviços estudados, arquiteturas montadas, configurações realizadas, testes executados e principais aprendizados obtidos em cada laboratório.

## Laboratórios

| Laboratório | Serviços principais | Descrição |
| --- | --- | --- |
| [Monitoring and Auditing with CloudWatch and CloudTrail](./monitoring-and-auditing-with-cloudwatch-and-cloudtrail/LAB-INFO.md) | EC2, CloudWatch, SNS, CloudTrail, S3, KMS | Configuração de monitoramento de CPU em uma instância EC2, alerta via SNS e auditoria de eventos com CloudTrail armazenando logs no S3. |
| [Fan-out Architecture with SNS, SQS and Lambda](./fan-out-architecture-with-sns-sqs-lambda/LAB-INFO.md) | SNS, SQS, Lambda, IAM, CloudWatch Logs | Implementação de uma arquitetura fan-out para distribuir eventos de pedidos de e-commerce para múltiplos consumidores desacoplados, com filtros SNS, SQS, DLQ e validação no CloudWatch Logs. |
| [Semana do Desenvolvedor - Sistema Serverless de Pedidos](./semana-dev-projeto/LAB-INFO.md) | API Gateway, Lambda, SQS, EventBridge, S3, DynamoDB, SNS, IAM, CloudWatch Logs | Construção de uma arquitetura serverless orientada a eventos para ingestão, validação, processamento, persistência, alteração e cancelamento de pedidos. |

## Temas de Estudo

Ao longo dos laboratórios, este repositório poderá abordar temas como:

- Computação com Amazon EC2
- Monitoramento com Amazon CloudWatch
- Auditoria e governança com AWS CloudTrail
- Armazenamento com Amazon S3
- APIs REST com Amazon API Gateway
- Notificações com Amazon SNS
- Mensageria assíncrona com Amazon SQS
- Processamento serverless com AWS Lambda
- Orquestração de eventos com Amazon EventBridge
- Persistência de dados com Amazon DynamoDB
- Segurança, IAM e controle de acesso
- Criptografia com AWS KMS
- Arquiteturas resilientes e escaláveis
- Arquiteturas orientadas a eventos
- Automação e práticas para aplicações cloud native

## Estrutura do Repositório

Cada laboratório possui sua própria pasta com a documentação e os arquivos relacionados:

```text
aws-labs/
+-- README.md
`-- nome-do-laboratorio/
    +-- LAB-INFO.md
    +-- imagens-do-lab.png
    `-- outros-arquivos-relacionados
```

## Sobre os Labs

Os laboratórios são documentados com foco em aprendizado prático. Sempre que possível, cada lab inclui:

- Objetivo do laboratório
- Cenário proposto
- Serviços utilizados
- Arquitetura
- Etapas realizadas
- Evidências visuais
- Resultado final
- Conhecimentos praticados
- Conclusão
