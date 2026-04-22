# redis-dba

Utilizei esse projetos para fins didatico baseado no video do youtube da Fernada Kipper chamado [Live Coding: Criando aplicação NODE JS do ZERO](https://www.youtube.com/watch?v=GVF--Rl3bP4&t=4314s), com pequenas alterações, especialmente na configuração da aws, inicialmente a aplicação utilizava o AWS SDK para o envio das mensagens, porém optei por usar uma ferramenta gratuita, nesse caso o Nodemailer.
Este projeto foi desenvolvido pela [Fernada kipper](https://github.com/Fernanda-Kipper) e [Guilherme Vahl](https://github.com/guivahl) como parte da disciplina de Banco de Dados Avançado do curso de Ciência da Computação da Universidade Federal de Pelotas. O objetivo principal é demonstrar o uso do banco de dados NoSQL Redis como message broker em um sistema de disparo de e-mails em lote.

Este projeto é um clone do repositório redis-dba, com algumas adições de funcionalidades.


## Tecnologias utilizadas

- [Redis](https://redis.io/)
- [NodeJs](https://nodejs.org/)
    - [Bull](https://github.com/OptimalBits/bull)
    - [Nodemailer](https://nodemailer.com/)

## Front-end da Aplicação

    - [membership-frontend](https://github.com/Fernanda-Kipper/membership-frontend)

## Como execultar o front-end

1. Clone o repositório

    ```
    git clone https://github.com/Fernanda-Kipper/membership-frontend
    ```

2. Navegue até a pasta do projeto

    ```
    cd membership-frontend
    ```

3. Instale as dependencias

    ```
    npm install
    ```

4. Rode o projeto com o comando 

    ```
    npm run dev
    ```

## Como executar

1. Clone o repositório e entre na pasta
2. Instale os pacotes utilizando o comando `npm install`
3. Crie um arquivo `.env` na raiz do projeto e insira suas credenciais de SMTP. Utilize o arquivo `.env.example` como base.
4. Rode o projeto com o comando `npm start`

### Exemplo de SMTP gratuito

Você pode usar um provedor com plano gratuito, como Mailtrap ou Brevo, informando no `.env` os dados do servidor SMTP fornecido por eles.
