
# Consumindo a API de Produtos

Para consumir a API de produtos, é necessário fazer uma solicitação GET para o endpoint `/api/products`. Além disso, você precisa incluir o cabeçalho `Authorization` com o valor `bearer <YOUR_API_TOKEN>`.

## Requisitos

- Você precisará de um token de API válido para acessar os recursos protegidos da API.
- Certifique-se de incluir o cabeçalho `Authorization` em todas as solicitações, conforme especificado.

## Exemplo de Solicitação

### Solicitação GET para /api/products

```http
GET /api/products HTTP/1.1
Host: your-api.com
Authorization: bearer <YOUR_API_TOKEN>
```

Exemplo de Resposta
A resposta da API será um JSON contendo uma lista de produtos. Cada produto será representado como um objeto com os seguintes atributos:

id: O identificador único do produto.
name: O nome do produto.
description: A descrição do produto.
price: O preço do produto.
category: A categoria do produto.
stock: O estoque disponível para o produto, representado como um objeto com tamanhos (se aplicável).
image: O URL da imagem do produto.
Aqui está um exemplo de JSON de resposta:


























# 🚀 Getting started with Strapi

Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/dev-docs/cli) (CLI) which lets you scaffold and manage your project in seconds.

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```
npm run build
# or
yarn build
```

## ⚙️ Deployment

Strapi gives you many possible deployment options for your project including [Strapi Cloud](https://cloud.strapi.io). Browse the [deployment section of the documentation](https://docs.strapi.io/dev-docs/deployment) to find the best solution for your use case.

## 📚 Learn more

- [Resource center](https://strapi.io/resource-center) - Strapi resource center.
- [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation.
- [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials made by the core team and the community.
- [Strapi blog](https://strapi.io/blog) - Official Strapi blog containing articles made by the Strapi team and the community.
- [Changelog](https://strapi.io/changelog) - Find out about the Strapi product updates, new features and general improvements.

Feel free to check out the [Strapi GitHub repository](https://github.com/strapi/strapi). Your feedback and contributions are welcome!

## ✨ Community

- [Discord](https://discord.strapi.io) - Come chat with the Strapi community including the core team.
- [Forum](https://forum.strapi.io/) - Place to discuss, ask questions and find answers, show your Strapi project and get feedback or just talk with other Community members.
- [Awesome Strapi](https://github.com/strapi/awesome-strapi) - A curated list of awesome things related to Strapi.

---

<sub>🤫 Psst! [Strapi is hiring](https://strapi.io/careers).</sub>
