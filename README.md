# Mega Starter (Frontend)

This is a starter Next.js template made for developers building on MegaETH. This app comes pre-configured with Reown (prev. WalletConnect).

By default, this app is set up to interact with a smart contract deployed on MegaETH testnet. You can find the address of this contract in src/constants/index.js.


## Getting Started
Install the Mega CLI if you don't have it already
```shell
npm install -g mega-cli
#or
pnpm add -g mega-cli
#or
yarn global add mega-cli
```

Create a new `.env` or `.env.local` file in the root directory and put your Reown Project ID there. Refer to `next-app/.env.example` for more details.

Run the app using this command:

```shell
mega dev
```

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Next.js
To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
