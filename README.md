
# TXN-My-Shelby-Guid
My Transaction Overview (TXN) for Phase 2 has been processed.  Previously, I had over 300 transactions, but they have been reset.
 ![Image Alt](

# Aptos x ShelbyUSD On-Chain Transaction Data (March 2026)

This repository contains a dataset of on-chain transactions from the **Aptos Blockchain**, extracted from a block explorer. The data captures a series of transfers and function calls performed within a specific timeframe on March 11, 2026.

## 📊 Dataset Overview

The dataset includes 183 transactions (sample provided in the code files) with the following attributes:

- **Version**: The unique transaction version/ID on the Aptos network.
- **Timestamp**: Exact time of the transaction (UTC).
- **Sender/Receiver**: Wallet addresses involved in the movement of assets.
- **Function**: The specific Move smart contract function executed (e.g., `transfer_coins`, `transfer_fungible_assets`).
- **Amount**: The quantity of APT tokens x SHELBYUSD transferred (positive for incoming, negative for outgoing).
- **Gas Fee**: The network fee paid for each transaction.

## 📂 File Formats

I have provided the data in two formats for ease of use:
1.  `aptos_transactions.json`: Best for web integration and application development.
2.  `aptos_transactions.csv`: Ideal for data analysis, Excel, or Python (Pandas) processing.

## 🛠 Usage

You can use this data for:
- Analyzing wallet behavior and transaction frequency.
- Testing blockchain indexing scripts.
- Visualizing gas fee trends on the Aptos X Shelby network.
