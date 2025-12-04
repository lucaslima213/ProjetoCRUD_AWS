# ProjetoCRUD_AWS

## Descrição do Projeto

Este projeto apresenta o passo a passo para criar uma aplicação web serverless de cadastro de produtos, utilizando o Amazon DynamoDB como banco de dados, AWS Lambda para executar operações CRUD (Create, Read, Update, Delete), integração via API Gateway e interface web hospedada no Amazon S3. O monitoramento da solução é realizado com o Amazon CloudWatch.

## O que foi construído

- **Backend Serverless:** Função Lambda em Python integrada ao DynamoDB para operações CRUD.
- **API REST:** API Gateway configurado com rotas para cada operação (GET, POST, PUT, DELETE).
- **Frontend Web:** Interface estática hospedada no Amazon S3, conectada à API via JavaScript.
- **Monitoramento:** Logs e métricas configurados no Amazon CloudWatch para acompanhamento das operações.
- **Segurança e Permissões:** Role IAM criada com permissões específicas para Lambda e DynamoDB.
- **Limpeza de Recursos:** Orientações para remoção dos recursos ao final do laboratório, evitando custos extras.

## Serviços AWS Utilizados

- **Amazon DynamoDB:** Banco de dados NoSQL para armazenar os produtos cadastrados.
- **AWS Lambda:** Execução das funções backend em Python para manipulação dos dados.
- **Amazon API Gateway:** Exposição das rotas da API REST para integração entre frontend e backend.
- **Amazon S3:** Hospedagem da interface web estática (HTML, CSS, JS).
- **Amazon CloudWatch:** Monitoramento e registro de logs das operações realizadas.
- **AWS IAM:** Gerenciamento de permissões e roles para acesso seguro aos serviços.

- ## Passos para Conclusão do Projeto

1. Criar uma Role IAM com permissões para Lambda e DynamoDB.
2. Criar uma tabela no DynamoDB para armazenar os produtos.
3. Desenvolver e configurar a função Lambda em Python, integrando-a ao DynamoDB.
4. Configurar o API Gateway com rotas para operações CRUD.
5. Hospedar a interface web no Amazon S3.
6. Ativar monitoramento com CloudWatch.
7. Validar o funcionamento da aplicação e realizar limpeza dos recursos utilizados.
