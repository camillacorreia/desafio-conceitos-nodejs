<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
    Desafio 02: Conceitos do Node.js
</h3>

<br>

# 🚀 Sobre o Desafio:

Neste desafio eu apliquei um pouco dos conhecimentos de NodeJS que obtive no Bootcamp GoStack 13.0 da RocketSeat para a criação de uma API no qual eu mostro os projetos criados ao longo do GoStack.

Algumas coisas que aprendi nesse primeiro módulo:

- A criar um Server local com Node.JS;
- Métodos HTTP;
- Tipos de Parâmetros;
- O que são Middlewares.

# 💻 Como testar a API criada:

- Clone este repositório no seu computador
- Com o projeto aberto você deve rodar os seguintes comandos em seu terminal para instalar as dependencias:

```shell
    yarn install / npm install
```

- Para iniciar a API você deve realizar o seguinte comando:

```shell
    yarn dev / npm run dev
```

- Para realizar testes na API:
```shell
    yarn test / npm run test
```

# 📌 Rotas para testar a API:

- **`POST - /repositories`** : Cria um repositório. Para esta rota temos que utilizar as seguintes declarações:

```json
    {
        "title": "Titulo do Repositório",
        "url": "Link URL do Repositório",
        "techs": ["Algumas", "Tecnologias", "Usadas"]
    }
```

- **`GET - /repositories`** : Retorna todos os Repositórios.

- **`PUT - /repositories/:id`** : Atualiza repositório. Esta rota necessita do ID do repositório que gostaria de alterar alem de utilizar as seguintes declarações:

```json
    {
        "title": "repository title",
        "url": "repository url",
        "techs": ["repo", "techs"]
    }
```

- **`DELETE - /repositories/:id`** : Deleta um repositório, Esta rota necessita do ID do repositório que gostaria de deletar.

- **`POST - /repositories/:id/like`** : Cria um Like para o repositório. Esta rota necessita do ID do repositório que gostaria de deixar o Like.

---

Feito com 💜 por [Camilla Correia](https://www.linkedin.com/in/camilla-correia-3203a3139/)