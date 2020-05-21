# Trybe Hexo Template

Template de configuração do [Hexo](https://hexo.io/pt-br/) para renderizar um portfólio simples em formato de timeline

## Uso

- No GitHub, clique em "Use this template" para criar um novo repositório
- Clone o repositório criado
    ```bash
    git clone <url> hexo-portfolio
    ```
- Acesse a pasta do repositórioo
    ```bash
    cd hexo-portfolio
    ```
- Inicialize o repositório do tema
    ```bash
    git submodule update --init
    ```
- Instale as dependências
    ```bash
    npm i
    ```
- Execute o hexo
    ```bash
    npm run server
    ```

### Criando novos posts

- Acesse a pasta do repositório
    ```bash
    cd hexo-portfolio
    ```
- Crie um novo post utilizando o scaffolding do Hexo
    ```bash
    npx hexo new "nome do post"
    ```

## Deploy

- Configure a opção de deploy desejada de acordo com a [documentação](https://hexo.io/pt-br/docs/one-command-deployment.html#Heroku)
- Execute o comando de deploy
    ```bash
    npm run deploy
    ```