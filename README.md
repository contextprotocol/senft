# xpNFTs (Experience-Driven Non-Fungible Tokens)

xpNFTs, short for Experience-Driven Non-Fungible Tokens, are dynamic and interactive tokens designed to revolutionize the way we think about digital assets in the Context ecosystem. As unique tokens, xpNFTs embody the core principle of non-fungibility, ensuring each instance is distinct and irreplaceable.

## Key Features of xpNFTs
- *Semantic Integration*: xpNFTs carry rich, meaningful metadata that evolves over time. This semantic layer allows the tokens to provide more context and meaning beyond simple ownership, enabling deeper connections and interactions within the ecosystem.
- *Provenance and Evidence*: xpNFTs maintain a transparent and immutable record of their history and changes on-chain. This provenance ensures authenticity, integrity, and trustworthiness, allowing users to verify the evolution and origins of each token.
- *Dynamic Attributes*: xpNFTs are not static. Their attributes can change based on user actions, achievements, or real-world events. This dynamism makes xpNFTs more engaging and valuable over time, as they can adapt and evolve in response to various stimuli.
# Getting started

## Modify, test and deploy your own NFT Contract
Edit contracts/NFTCollection and test the contract
```shell
npm run test
```

## Create your domain in Context
Go to https://app.ctx.xyz, register and create a new domain.

Your domain will look like ctx_name123, but if you plan to go to production get a proper name and be verified. Reach us out here.

For your domain get and API key (CONTEXT_APIKEY).

Edit your .env (copy .env.example to .env)
- CONTEXT_APIKEY: get it from the Context App after registering.
- BLOCKHAIN_RPC: Blockchain RPC (Infura, Alchemy...)
- WALLET_PRIVKEY: The private key (the owner of the Contract).

Make sure the wallet has enough funds to mint the NFTs.
```shell
npm run init
```

This script will:
1. Deploy the NFT Smart Contract
2. Upload the assets (image)
3. Create the metadata in Context for the NFT Contract

# Drops : Mint NFTs

Edit comnf,. drops.
You are ready to mint an NFT
```shell
npm run drop gen0
```

## Drops
You are ready to mint an NFT
```shell
npm run mint
```