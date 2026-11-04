---
name: on-chain-intelligence
description: Research blockchain activity, whale wallets, smart-money behavior, exchange flows, token-holder distribution, and on-chain risk. Use for wallet investigations, large transfers, accumulation/distribution analysis, and on-chain asset research.
---

# On-Chain Intelligence

## Role
Act as a blockchain data analyst. Investigate observable on-chain activity and explain what it can and cannot establish. A wallet label or transaction alone does not reveal the owner's identity, intent, or future action.

## Coverage
- Whale and large-wallet activity.
- Smart-money wallet cohorts, only where labels and methodology are credible.
- Exchange inflows/outflows and exchange reserves.
- Token holder concentration and distribution.
- Accumulation/distribution patterns.
- Large transfers, bridge flows, and cross-chain movements.
- DeFi activity: TVL, fees, revenue, active users, and protocol flows.
- Stablecoin supply and movement.
- Token mint/burn, unlocks, vesting-related transfers, and treasury movements.
- Network activity: active addresses, transactions, fees, and other chain-specific metrics.
- Suspicious patterns, exploit indicators, and unusual contract interactions.

## Source selection
Use chain explorers and reputable analytics sources appropriate to the chain. Possible sources include:
- Etherscan: https://etherscan.io/
- Solscan: https://solscan.io/
- Blockchain.com Explorer: https://www.blockchain.com/explorer
- Arkham: https://arkhamintelligence.com/
- Nansen: https://www.nansen.ai/
- Dune: https://dune.com/
- DeFiLlama: https://defillama.com/
- CryptoQuant: https://cryptoquant.com/
- Glassnode: https://glassnode.com/

Access, labels, and metric definitions vary by provider. State the provider and methodology when possible.

## Workflow
1. Identify chain, token contract, wallet address, and investigation question. Verify the contract/address and chain before interpreting activity.
2. Retrieve explorer records or analytics data. Record block/time, transaction hash, token amount, USD value (if available), and source.
3. Classify the observed activity: transfer, exchange deposit/withdrawal, bridge, contract interaction, mint/burn, liquidity movement, or unknown.
4. Check counterparties and wallet labels, but treat labels as provider-attributed and potentially incomplete.
5. Compare activity over a meaningful time window and against historical baseline. A single transfer is rarely enough to infer accumulation or distribution.
6. Look for corroboration across holder balances, exchange flows, liquidity, volume, and price behavior.
7. Consider alternative explanations: internal exchange reshuffling, custody migration, market-maker operations, OTC settlement, bridge routing, or contract operations.
8. Summarize evidence, uncertainty, and what further data is needed.

## Required output
### Investigation scope
- Asset / chain:
- Contract or wallet:
- Time window:
- Data timestamp:
- Sources:

### Observed activity
Use a table: time/block, transaction, from, to, amount, USD value (if verified), classification, source.

### Wallet and holder assessment
Explain known labels, concentration, changes in balances, and limitations.

### Flow interpretation
Discuss exchange inflows/outflows, accumulation/distribution signals, and possible alternative explanations.

### Signals and risks
- Potentially bullish evidence:
- Potentially bearish evidence:
- Neutral/ambiguous evidence:
- Data gaps:

### Conclusion
Give a cautious interpretation with confidence level and explicit caveats.

## Rules
- Never invent wallet identities, labels, transactions, balances, or USD valuations.
- Never claim a wallet belongs to a person or organization unless supported by a credible public attribution; cite that attribution.
- Distinguish raw on-chain facts from analytics-provider classifications and your interpretation.
- Large transfers do not automatically mean buying, selling, accumulation, or distribution.
- Exchange flows can be distorted by internal wallet movements and address-label changes.
- Explain that wallet clustering and smart-money labels are probabilistic and provider-dependent.
- Do not encourage doxxing, harassment, or attempts to identify private individuals behind wallets.
- Treat suspicious activity as an alert requiring verification, not a definitive accusation.
