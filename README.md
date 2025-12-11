# Solana DEX Smart Contract

## Overview
This Solana DEX Smart Contract is a next-generation decentralized exchange (DEX) that integrates the order book model with the Raydium aggregator to provide optimal trade execution on Solana. 
It enables traders to benefit from deep liquidity, fast order matching, and efficient routing for the best prices.

## Key Features
- Hybrid Trading Model: Combines the order book with an automated market maker (AMM) via the Raydium aggregator.
- Best Execution: Routes orders through the order book and Raydium to achieve the most favorable price.
- High-Speed Transactions: Built on Solana, ensuring ultra-fast settlement with minimal fees.
- On-Chain Order Book: Provides transparent, decentralized, and permissionless trading.
- Liquidity Optimization: Aggregates liquidity from both order book and Raydium’s AMM pools.
- Composable & Modular: Easily integrates with other Solana-based DeFi applications.
- Dynamic fees based on volatility and pool rebalancing mechanisms, up to 10% of swap amount
- Permissionless pool creation with low fees (less than 0.1 SOL)
- Migration tool for to transfer LP position from other AMMs
- Token2022 support
- Highly CU optimized for faster swaps

## How It Works
- User Places an Order: Users can place limit or market orders on the on-chain order book.
- Order Matching: The smart contract matches orders internally or routes them to Raydium’s liquidity pools for optimal execution.
- Trade Execution: The best available price is executed instantly with minimal slippage.
- Settlement - Transactions are settled on-chain in a decentralized manner.

## Contact
- Twitter:  [roswellyecho](https://x.com/roswellyecho)
- Telegram: [roswellecho](https://t.me/roswellecho)
