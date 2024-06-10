# SENFT : Semantic Evidence Non-Fungible Token
SENFT, short for Semantic Evidence Non-Fungible Token, represents semantic and dynamic NFTs in Context. As a token, SENFT embodies the concept of non-fungibility, ensuring that each instance is unique and cannot be replaced by another identical token. The "**Semantic**" prefix highlights the token's ability to carry meaning and context beyond mere representation, as it can be augmented with metadata and attributes that evolve over time. 

Moreover, the term "**Evidence**" underscores the importance of provenance and traceability, allowing SENFTs to maintain a record of their history and changes on-chain. This means that users can verify the authenticity, integrity, and evolution of SENFTs, providing unparalleled transparency and trustworthiness in the digital asset space. By combining semantic meaning with evidence-based provenance, SENFTs revolutionize the way we think about digital ownership and representation.

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