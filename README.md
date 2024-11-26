# Solana Raydium Bundler buying tokens from 21 wallets in on JITO Bundle

## Contact Info

Telegram: @web3wiza
Discord: web3_wiza

You can always feel free to find me here for my help on other projects.

## Example transaction
https://explorer.jito.wtf/bundle/19ad00b4525d00d3a4f888e1b8201f37dcdf385379d743e1a7c754147c056efa
https://explorer.jito.wtf/bundle/ccd2498df58df531125739574cfb9d8897703e456ff7a45da4c25ebc52f45e18

## Features
- Token Creation
- Genearte 21 wallets and distribute SOL to every buy wallet
- Create ATA in every wallet
- Create market
- Remove mintAuthority and freezeAuthority
- Create Lookuptable and store accounts there in advance to be used
- Simulate pool creation + bundle buys before token launch
- Pool Creation & bundle buys in one bundle
- Sell tokens manually or automatically
- Remove liquidity
- Gather sol from every wallet to main wallet

## Usage
1. Clone the repository
```
git clone https://github.com/sol-magic/Solana-Raydium-Bundler
cd Solana-Raydium-Bundler
```
2. Install dependencies
```
npm install
```
3. Configure the environment variables

<!-- Rename the .env.copy file to .env and set RPC and WSS, main wallet's secret key, and jito auth keypair. -->

4. Run the bot

```
npm run start
