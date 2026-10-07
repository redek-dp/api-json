<img src="https://github.githubassets.com/assets/actions-any-lang-f603eeb8cd45.svg" min-width="150px" max-width="150px" width="150px" align="right" alt="">

# API-JSON.

``API-JSON`` - DEPLOY JSON SERVER TO VERCEL...

----------

A TEMPLATE TO DEPLOY ``JSON SERVER`` TO ``VERCEL``, ALLOW YOU TO RUN FAKE REST API ONLINE!

----------

## DEMO FROM THIS REPOSITORY

```bash
https://api-json-roan.vercel.app/
```
--------

### OU

```bash
https://api-json-roan.vercel.app/api/posts
```

--------

### COMO USAR

1. CLIQUE EM "**USE THIS TEMPLATE**" OU CLONE ESTE REPOSITÓRIO.
2. ATUALIZE OU UTILIZE O ARQUIVO [`DB.JSON`](./DB.JSON) PADRÃO DO REPOSITÓRIO.
3. CADASTRE-SE OU FAÇA LOGIN NA [VERCEL](HTTPS://VERCEL.COM).
4. NO PAINEL DA VERCEL, CLIQUE EM "**+ NEW PROJECT**" E, EM SEGUIDA, EM "**IMPORT**" PARA IMPORTAR SEU REPOSITÓRIO.
5. NA TELA "**CONFIGURE PROJECT**", MANTENHA AS CONFIGURAÇÕES PADRÃO E CLIQUE EM "**DEPLOY**".
6. AGUARDE A CONCLUSÃO DO DEPLOY E SEU SERVIDOR JSON ESTARÁ PRONTO PARA USO!

## PADRÃO `db.json`

```json
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```

## HABILITAR OPERAÇÕES DE ESCRITA

VOCÊ PODE ENCONTRAR O CÓDIGO DE EXEMPLO EM [`API/SERVER.JS`](./API/SERVER.JS).

## REFERÊNCIA

1. https://github.com/typicode/json-server
2. https://vercel.com
