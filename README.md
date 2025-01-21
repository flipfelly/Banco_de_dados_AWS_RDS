# Criando Banco de Dados no AWS RDS com integração com Python

Este repositório contém um notebook desenvolvido como parte do curso de Engenharia de Dados ministrado pelo Professor Fernando Amaral. Nesta atividade, exploramos a criação e população de um banco de dados PostgreSQL hospedado no AWS RDS, utilizando Python para automatizar as etapas.

## 🔍 Visão Geral

O notebook oferece um passo a passo prático, abordando:

1. **Configuração da Infraestrutura:**
   - Criação de uma instância RDS na AWS.
   - Configuração de permissões e acesso.

2. **Banco de Dados:**
   - Criação de tabelas e definição de esquemas.
   - Configuração de conexão com o PostgreSQL.

3. **População dos Dados:**
   - Upload de arquivos para o bucket S3.
   - Carregamento dos dados no RDS.

4. **Análise e Consultas:**
   - Execução de consulta SQL para validação.

## 🛠️ Requisitos

Para executar este notebook, você precisará de:

- Conta ativa na AWS.
- Permissões para criar instâncias RDS e buckets S3.
- Python com as bibliotecas:
  - `boto3` (interação com AWS).
  - `psycopg2` (conexão com PostgreSQL).

## 🔧 Como Utilizar

1. Abra o notebook em um ambiente compatível, como Jupyter Notebook ou Google Colab.

2. Configure as credenciais da AWS no arquivo ou ambiente apropriado.

3. Siga as instruções detalhadas no notebook para:
   - Configurar o RDS.
   - Criar e popular o banco de dados.

4. Certifique-se de liberar os recursos provisionados após o uso para evitar cobranças.

## ✨ Destaques

- **Automatização:** Utilização de Python para configurar e gerenciar a infraestrutura.
- **Integração AWS:** Uso combinado de RDS e S3.




