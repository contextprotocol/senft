# Synamic NFTs using Context
Create Dynamic NFTs using Context
Link to the tutorial

# Getting started

## Modify, test and deploy your NFT Contract
This step is using the metadata created in Step one, don't miss it.

Edit/Verify contracts/NFTCollection and test
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

# Mint NFTs

## Single NFT
You are ready to mint an NFT
```shell
npm run mint
```

## Drops
You are ready to mint an NFT
```shell
npm run mint
```

# Marketplace
## Sell
## Buy
## Bid