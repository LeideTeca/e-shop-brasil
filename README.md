
# E-Shop Brasil

## Sistema de Gestão de Clientes e Pedidos

Projeto acadêmico desenvolvido para demonstrar a aplicação de tecnologias de banco de dados e Big Data em uma empresa de comércio eletrônico.

## 1. Objetivo do projeto

Desenvolver um sistema para cadastrar, consultar e editar clientes e pedidos, utilizando Python, Streamlit e MongoDB.

## 2. Tecnologias utilizadas

- Python: linguagem de programação.
- Streamlit: criação da interface do sistema.
- MongoDB: banco de dados NoSQL.
- PyMongo: conexão entre Python e MongoDB.
- Pandas: manipulação e organização dos dados.
- Docker: configuração do ambiente de execução.

## 3. Funcionalidades

- Cadastro de clientes.
- Cadastro de pedidos.
- Consulta de clientes.
- Edição de dados dos clientes.
- Consulta de pedidos.
- Integração dos dados de clientes e pedidos.
- Relatórios de vendas.
- Visualização gráfica do faturamento.

## 4. Organização do banco de dados

O banco de dados utilizado é o MongoDB, com duas coleções principais:

- clientes: armazena os dados dos clientes.
- pedidos: armazena os dados das compras realizadas.

A integração entre as coleções permite relacionar os pedidos aos respectivos clientes.

## 5. Como executar o projeto

Com o Docker Desktop instalado e em funcionamento:

1. Baixe ou clone este repositório.
2. Abra o terminal na pasta do projeto.
3. Execute:

```bash
docker compose up --build
```

4. Acesse no navegador:

```text
http://localhost:8501
```

## 6. Execução sem Docker

Com Python instalado e as dependências configuradas:

```bash
pip install -r requirements.txt
python -m streamlit run app.py
```

## 7. Segurança

As informações de conexão com o banco de dados devem ser armazenadas em variáveis de ambiente. Senhas e dados de acesso não devem ser publicados no GitHub.

## 8. Considerações finais

O projeto demonstra como Python, Streamlit, MongoDB e Docker podem ser utilizados em conjunto para desenvolver uma aplicação de gestão de clientes e pedidos, integrando dados e apresentando informações úteis para a tomada de decisões.

Projeto acadêmico — E-Shop Brasil.
