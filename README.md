# Crateful

A permissionless, zero-fee NFT marketplace built on [Arc Testnet](https://arc.network), the EVM-compatible L1 by Circle where USDC is the native gas token.

**Live site:** <https://crateful.netlify.app>

## Features

- Browse listings without connecting a wallet
- Connect any wallet (MetaMask) to mint, buy, sell, or view owned NFTs
- Mint an NFT directly from an uploaded image, no IPFS pinning service required, metadata and image are stored fully on-chain
- List and buy NFTs from any collection on Arc Testnet, not just this one
- Zero platform fee, non-custodial, the NFT stays in the seller's wallet until it sells
- View all NFTs owned by a connected wallet across this collection and any collection that has been listed on the marketplace

## Stack

- Two Solidity contracts: an ERC-721 collection (`ArcNFT`) and a marketplace contract (`ArcMarketplace`)
- Deployed with Hardhat
- Frontend: vanilla JS + [ethers.js](https://docs.ethers.org/), no backend, no database
- Hosted on Netlify

## Network

- Chain: Arc Testnet
- Chain ID: 5042002
- RPC: <https://rpc.testnet.arc.network>
- Explorer: <https://testnet.arcscan.app>
- Faucet: <https://faucet.circle.com>

## Status

Testnet only. No real monetary value.
