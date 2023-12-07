# Desafio-Sicredi-Engenharia-de-Dados
Este projeto demonstra como criar um pipeline de ETL para um Data Lake usando um framework de processamento distribuído para Big Data.

## Desafio:
- Modelar a estrutura do banco de dados para os dados de movimentações dos cartões.
- Inserir uma massa de dados fictícia nas tabelas.
- Criar um componente capaz de ler os dados das tabelas e escrever um único arquivo flat, em um diretório local.

Solução:
-------
### A solução proposta para o desafio é a seguinte:
- O banco de dados é modelado usando JSON para que seja reutilizável caso necessário, manutenção fácil.
- A massa de dados fictícia é inserida nas tabelas usando a linguagem SQL.
- O componente ETL é implementado usando o framework Spark.
- O arquivo CSV é escrito usando a biblioteca Apache Spark CSV.
- Utilizei Docker Compose para facilitar a execução da aplicação.

Execução:
-----
### Para executar o projeto:
1. Clone o repositório do projeto.
2. Execute docker-compose up -d no diretório.
3. Instale as dependências do projeto usando o comando pip install -r requirements.txt.
4. Execute o comando python runner.py para iniciar o pipeline de ETL.
----
### Dificuldades e obs:
Foi proposto como bônus no desafio um ambiente em Docker, no qual não tenho tanta familiaridade, mas foi bem divertido aprofundar sobre.
Utilizei o Databricks para executar a lógica feita no projeto e, se tivesse mais tempo, documentaria o processo e colocaria aqui. 
