# solana_tokens_data

### **Thesis:**

- Solana is a relatively insulated ecosystem, not much places for capital to leak to
- Solana users recently received capital in terms of Pyth, JTO, JUP airdrops
- The capital will flow into the next layer of projects, meme, nfts, etc..

### **Opportunity:**

- Use a classifier model to find which tokens have the highest likelihood of increasing their value by 100%
    - Why a classifier model instead of a time series price predication model?
        - Early tokens might not have much historical data
        - Classifier are a simpler problem to solve increase of price predication
     
### **Dataset:**

- All solana token transfers
- Exclude tokens that will affect the learning
    - SOL
    - WBTC
    - WETH
    - WSOL
    - stablecoins
    - Staked SOL
    - Bridged bluechip tokens

Full documentation here by Jason Xu [here] (https://jbxu.notion.site/Solana-Indicators-Doc-5a67662458c2496ab75810d19084ebca)
