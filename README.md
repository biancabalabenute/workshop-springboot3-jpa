# workshop-springboot3-jpa
Está aplicação foi desenvolvida seguindo o curso Java COMPLETO do Nelio Alves, utilizando Java Spring e Spring MVC, para criação do servidor, Spring Data JPA para manipulação e persistência de dados, Lombok para geração de boilerplates e Postgres Driver para realizar a conexão com banco de dados Postgress. Além do H2 para o ambiente de teste.

## Requisitos
Para rodar esse projeto você precisa ter o Java 17 instalado na sua máquina.

## Ambiente de desenvolvimento usado
Este projeto foi desenvolvido utilizando as seguintes ferramentas:

- **IntelliJ IDEA**: Uma poderosa IDE para desenvolvimento Java, utilizada para escrever, depurar e executar o código do projeto.
- **Maven**: Ferramenta de automação de compilação utilizada para gerenciar as dependências do projeto e realizar builds.
- **PostgreSQL**: Banco de dados relacional utilizado para persistência de dados. Recomenda-se a utilização do pgAdmin ou de outras ferramentas de administração para gerenciar o banco de dados.
- **H2 Database**: Banco de dados em memória utilizado para ambiente de teste.
- **Postman**: Uma plataforma de colaboração para desenvolvimento de APIs. Utilizado para testar endpoints e realizar requisições HTTP durante o desenvolvimento da aplicação.

Certifique-se de ter essas ferramentas instaladas e configuradas corretamente para uma experiência de desenvolvimento sem problemas.

## Instalando o projeto

Primeiro você deve clonar o repositório,

```bash
# Clone o repositório
$ git clone https://github.com/biancabalabenute/workshop-springboot3-jpa.git

# Acesse-o
$ cd workshop-springboot3-jpa.git
```

Agora, dentro do IntelliJ, instale as depedências com o Maven.

## Banco de dados
Para o banco estou usando o PostgreSQL na porta padrão 5432. Importante criar um BD com o nome springboot-course. Mude a senha para a que você definiu quando instalou o BD.


## Executando o arquivo
Por fim, você pode executar o programa pelo arquivo **CourseApplication.**
