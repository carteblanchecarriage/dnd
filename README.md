# D&D Character Generator

![page1](https://github.com/carteblanchecarriage/dnd/assets/115643776/2c4299b4-c687-4af5-a5ee-5552ef31884e)

> Imagine, creating a new D&D Character on fastcharacter.com (just a few clicks, lets go!), copy it into our website and BOOM! Having a custom AI generated avatar minted and saved into Dragons Mine for for your level 1 Dragonborn, all in under a minute! Download for free or save your character as NFT with a random secret/public mission. Are we having fun yet?

# Blockchain, Chainlink & IPFS

- Our database of dragonborn heroes is maintained as NFTs in our smart contract, with a nice royalty for our treasury in there. - [@Cromewar put a](https://danj-o.notion.site/Just-regular-NFTs-7e555cc179684be58edf002b0f5b645d) sentence or two and a link here. -

- In the past, we used Chainlink in our Smart Contract to provide VRF randomness. [Link](https://goerli.etherscan.io/address/0xa41a00db6c90b969252b38580e36b5241c16de85) In the future we want to expand this random seed into unique image prompts, gameplay missions and DM/GM approved mission complete access control. [See Our Github Repo for mo'](https://github.com/DnDnDiffusion/scaffold-dnd)

- We used IPFS/NFT.Storage to provide decentralized, permanent and immutable storage for the image saved to NFT. [link to code in front end, line 42](https://github.com/DnDnDiffusion/Front-end/blob/0d8ea121eb9e9f05550a99e6ae4e6887642e5e1b/pages/index.jsx#L42) and more code at [util for NFT Storage](https://github.com/DnDnDiffusion/Front-end/blob/main/utils/web3utils.js).


## Front-end setup

> `npm install` from the front-end directory to install dependencies

First, run the development server from the front-end directory:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.jsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/getImage](http://localhost:3000/api/getImage). This endpoint can be edited in `pages/api/getImage.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

Use the `utils/` folder to add general functions (such as generating prompts, or saving files to NFT.Storage)



This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


