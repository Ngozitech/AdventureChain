# ExplorerPass

## Adventure Credits Token System

ExplorerPass is a blockchain-based rewards and tokenization platform for the adventure tourism industry. The platform leverages Clarity smart contracts to create a complete ecosystem for adventure operators, guides, and enthusiasts.

## Overview

AdventureChain's ExplorerPass implements a fungible token system (ADV tokens) that enables:

- Tokenized adventure activities and experiences
- Reward points for outdoor enthusiasts
- Partner ecosystem for adventure providers
- Staking mechanism for community governance
- Seasonal promotions with adjustable reward multipliers

## Key Features

- **Token Economics**: ADV tokens serve as the currency within the ecosystem with a maximum supply of 500 billion tokens
- **Adventure Rewards**: Users earn ADV tokens by participating in adventure activities
- **Booking System**: Book experiences directly through partner adventure providers
- **Staking Mechanism**: Stake tokens to participate in governance and earn rewards
- **Partner Network**: Community-driven partnership model with voting rights for stakeholders
- **Seasonal Adjustments**: Dynamic reward multipliers to incentivize activities during specific seasons

## Technical Details

- Token Name: Adventure Credits
- Token Symbol: ADV
- Decimals: 8
- Minimum Stake: 2,500 ADV
- Initial Supply: 2.5 billion ADV
- Governance: Stake-weighted voting for partner proposals

## Getting Started

1. Clone the repository
2. Deploy the smart contract to your blockchain node
3. Initialize the contract with your wallet as the owner
4. Add initial partners through the admin interface
5. Set the appropriate seasonal multiplier

## Contract Functions

- `mint`: Create new tokens (owner only)
- `burn`: Remove tokens from circulation
- `earn-from-activity`: Reward users for adventure activities
- `book-adventure`: Book experiences with partners
- `stake`/`unstake`: Participate in governance
- `propose-partner`/`vote-for-partner`: Community governance
- `add-partner`: Add approved adventure providers (owner only)
- `set-season-multiplier`: Adjust seasonal rewards (owner only)