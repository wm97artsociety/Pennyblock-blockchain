# Pennyblock-blockchain

# Pennyblock W1 Blockchain — Project Overview & User Guide

## Introduction


add this tokens to mint to token contract for rate of eth to penny amount if eth gives $3000 you should get 300,000 penny stocks 


tokensToMint = (ethAmount * ethUsdPrice) / 0.01;

Pennyblock is a custom, EVM-compatible Layer 2 blockchain designed to revolutionize token economics through a unique penny-stock style token model. The native token, **TOEKEN**, provides exponentially greater token rewards for smaller ETH deposits, encouraging micropayments, broad participation, and organic liquidity growth. Combined with a multi-chain universal payment gateway, anti-dump safeguards, and lazy NFT minting, Pennyblock offers a robust and user-friendly ecosystem for token holders, liquidity providers, and traders.

---

## Key Features & How It Works

### Penny-Stock Style Tokenomics

- Depositing 1 ETH mints mints TOEKEN tokens price through eth.



- Smaller ETH deposits mint proportionally more tokens, incentivizing microtransactions.
- Liquidity providers can add ETH liquidity to increase the token’s base minting rate, effectively boosting token value over time.
- This dynamic minting mechanism simulates a live liquidity order book that rewards early participation.

### Anti-Dump Protection (7% Volatility Lock)

- If a single transaction or cumulative sales within 24 hours exceed **7% of the total TOEKEN supply**, all token transfers are locked for 24 hours to prevent market crashes.
- During this lock period, no token sales or transfers can occur, acting as a circuit breaker to stabilize the token price.
- To lift the lock, the community must **repurchase at least 14% of the total supply** within the lock period, after which normal trading resumes.
- This mechanism promotes market stability, deters large dumps, and safeguards investor value.

### Universal Multi-Chain Payment Gateway Integration

- Pennyblock integrates seamlessly with a zero-fee, multi-chain universal crypto payment gateway supporting ETH and any ERC-20 tokens across Ethereum, Base, Polygon, Arbitrum, and Optimism.
- Payments through the gateway are detected by a backend relayer which converts the paid amount into “penny value” and triggers minting of TOEKEN tokens accordingly.
- This creates a smooth, gas-optimized flow for micro-payments and multi-chain bridging into the Pennyblock ecosystem.

### Lazy NFT Minting

- NFTs are minted lazily on demand after successful payments, reducing gas costs and enhancing user experience.
- NFTs can serve as rewards, receipts, or digital assets tied to payment events.

---

## User Guide

### For Liquidity Providers

- Add ETH liquidity to Pennyblock via the designated function to raise the token mint rate.
- Increasing liquidity rewards future token buyers with fewer tokens per ETH, effectively raising token price.
- Benefit from contributing to the ecosystem’s stability and growth.

### For Token Holders & Traders

- Avoid selling 7% or more of total supply at once to prevent triggering the 24-hour transfer lock.
- Purchases during a lock help unlock trading by meeting the 14% repurchase threshold.
- Holding tokens is protected from large dumps, promoting confidence in the ecosystem.
- Consider adding liquidity to boost token value and mint rates.

---

## Token Value Growth & Volatility Lock Impact

Pennyblock’s design supports sustained token growth and liquidity by enforcing trading discipline and incentivizing steady profits.

- Starting with a **100-token share** representing 100 penny stocks, the token price appreciates by **7% per volatility cycle**.
- Assume **4 trades per day**, each generating a 7% profit before hitting the anti-dump lock threshold.
- After each 7% increase, the system locks transfers until sufficient rebuying occurs, preventing price crashes and encouraging liquidity replenishment.

### Growth Projection at 7% Profit per Volatility Section:

| Time Frame | Token Value Multiplier (approximate) |
|------------|-------------------------------------|
| 1 Day      | ~1.31× (4 cycles of 7%)              |
| 1 Week     | ~6.92×                              |
| 1 Month    | ~30.43×                             |
| 1 Year     | ~1,755×                             |
| 24 Years   | ~1.1×10^22                         |
| 50 Years   | ~1.3×10^44                         |
| 100 Years  | ~1.8×10^88                         |

> **Note:** These multipliers are theoretical and assume consistent 7% profits per cycle, with anti-dump locks ensuring liquidity stability by preventing large sell-offs.

### How the Volatility Lock Supports Growth

- By locking token transfers after 7% of supply is dumped, Pennyblock prevents destructive sell-offs that can kill liquidity.
- This encourages steady buybacks, ensuring the token maintains momentum and price appreciation.
- Liquidity providers further support growth by increasing minting rates through ETH contributions, compounding token value gains.

---

## Technical Summary

- The TOEKEN contract monitors transfer volumes and triggers a **24-hour lock** if a 7% dump threshold is exceeded.
- Transfer restrictions remain until 14% repurchase is detected, ensuring price stability.
- Liquidity additions dynamically adjust minting rates, fostering organic growth.
- Bridge contracts and relayers enable cross-chain minting tied to payments made through the universal gateway.
- Chainlink oracles provide real-time price data to maintain fair penny-value conversions.

---

## Conclusion

Pennyblock W1 Blockchain combines innovative tokenomics, robust anti-dump safeguards, and seamless multi-chain interoperability into a unique ecosystem optimized for penny-stock style crypto assets and universal payments. Its smart design empowers users to benefit from microtransactions, rewards liquidity providers, and stabilizes markets through intelligent volatility locks — all while integrating with a zero-fee, multi-chain payment gateway and lazy NFT minting infrastructure.

---

## Token Value Growth & Volatility Lock Impact (With Dollar Estimates)

Pennyblock’s design supports sustained token growth and liquidity by enforcing trading discipline and incentivizing steady profits.

- Starting with a **100-token share**, each token initially valued at **$0.01** (1 penny), the total starting value is **$1.00**.
- The token price appreciates by approximately **7% per volatility cycle**.
- Assume **4 trades per day**, each generating a 7% profit before hitting the anti-dump lock threshold.
- After each 7% increase, the system locks transfers until sufficient rebuying occurs, preventing price crashes and encouraging liquidity replenishment.

### Growth Projection with Dollar Values

| Time Frame | Token Amount (TOEKEN) | Approximate USD Value (@ token price)       |
|------------|----------------------|---------------------------------------------|
| 1 Day      | 131 tokens           | $1.31                                      |
| 1 Week     | 692 tokens           | $6.92                                      |
| 1 Month    | 3,043 tokens         | $30.43                                     |
| 1 Year     | 175,500 tokens       | $1,755                                     |
| 24 Years   | ~1.1 × 10^22 tokens  | ~$1.1 × 10^20 (100 quintillion USD)        |
| 50 Years   | ~1.3 × 10^44 tokens  | ~$1.3 × 10^42 (1.3 tredecillion USD)       |
| 100 Years  | ~1.8 × 10^88 tokens  | ~$1.8 × 10^86 (1.8 quindecillion USD)      |

> **Notes:**  
> - These numbers are approximate and assume continuous, consistent 7% gains per trade cycle with no interruptions.  
> - The anti-dump lock mechanism ensures liquidity is preserved, preventing massive sell-offs that could undermine growth.  
> - Liquidity providers and market participants contribute to sustaining this growth by adding liquidity and participating in repurchase cycles.

### What Does This Mean for You?

- Starting with a modest $1 investment, your holdings could grow exponentially with disciplined trading and a stable liquidity environment.  
- The anti-dump lock protects your investment from sudden market crashes, ensuring longevity and consistent value appreciation.  
- The model incentivizes steady growth rather than risky dumps, fostering a healthy and thriving token economy.

---
