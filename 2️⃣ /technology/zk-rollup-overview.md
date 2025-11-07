# What is a zk-Rollup?

A zk-Rollup (Zero-Knowledge Rollup) is a Layer 2 protocol that processes transactions off-chain and posts cryptographic proofs on-chain to confirm their validity.

Instead of every node re-executing transactions, Ethereum nodes simply verify a succinct proof (usually a zk-SNARK or zk-STARK).  
This drastically reduces gas costs and increases throughput, while keeping the same security guarantees as the base layer.

### Key Properties
- **Security:** Inherits the security of Ethereum  
- **Scalability:** Thousands of transactions per proof  
- **Privacy (optional):** ZKPs can hide transaction data  
- **Finality:** Proof-based validation prevents fraud or reorgs  

Zk-Rollups are the most mathematically elegant path toward scalable, trust-minimized blockchains.
