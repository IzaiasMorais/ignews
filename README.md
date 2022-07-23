<h1 align='center'>
Ignews Blog 💻
</h1>

<p align="center">Um pequeno blog privado</p>


## 📃 About the project



### Functionalities

- Autenticação pelo Github com NextAuth.
- Pagamentos via Stripe API.
- Armazenamento de dados com FaunaDB.
- Listagem de dados com GraphQL através do Apollo.

## 🚀 Technologies

- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Stripe](https://stripe.com/en-br)
- [FaunaDB](https://fauna.com/)
- [GraphQ](https://graphql.org/)
- [GraphCMS](https://hygraph.com/)
- [ApolloClient](https://www.apollographql.com/docs/react/)

## 💻 Cloning project

```bash
$ git clone https://github.com/IzaiasMorais/ignews.git && cd ignews
```

```bash
# Install the dependecies
$ npm i

# Run Stripe Webhook Listener
$ stripe listen --forward-to localhost:3000/api/webhooks

# Run the project
$ npm run dev
```





