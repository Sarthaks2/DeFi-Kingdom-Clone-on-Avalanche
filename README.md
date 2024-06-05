# DeFi-Kingdom-Clone-on-Avalanche

## Avalanche Subnets: Token Management on the Avalanche Blockchain

Welcome to Avalanche Subnets! This repository contains two powerful Solidity smart contracts: `ERC20.sol` and `vault.sol`. The `ERC20.sol` contract establishes a foundational ERC-20 token with crucial functionalities like transfer, approve, mint, and burn. Meanwhile, the `vault.sol` contract acts as a robust storage solution, ensuring secure management of the ERC-20 token, facilitating deposits, withdrawals, and maintaining supply and individual balances.

## Getting Started with Remix:

### Prerequisites:

1. **Remix IDE Setup**: Install Remix IDE on your web browser.
2. **Ethereum Wallet Compatibility**: Ensure compatibility with an Ethereum wallet (e.g., MetaMask) for seamless interaction with contracts on the Avalanche blockchain.

### Steps:

1. **Open Remix IDE**:
   - Launch Remix IDE in your web browser.

2. **Import Contracts**:
   - Copy the content of `ERC20.sol` and `vault.sol`.
   - Create new files named `ERC20.sol` and `vault.sol` within Remix.
   - Paste the respective contents into each file.

3. **Compile Contracts**:
   - Access the "Solidity" tab within Remix.
   - Choose the appropriate Solidity compiler version (e.g., ^0.8.17).
   - Click the "Compile" button to compile the contracts.

4. **Deploy Token Contract**:
   - Navigate to the "Deploy & Run Transactions" tab.
   - Select `ERC20.sol` in the contract dropdown.
   - Click "Deploy" to commence the deployment of the ERC-20 token contract.

5. **Copy Token Address**:
   - After deployment, copy the token contract address from the Remix console.

6. **Deploy Vault Contract**:
   - Choose `vault.sol` in the contract dropdown.
   - Paste the ERC-20 token contract address into the constructor parameter for Vault.
   - Click "Deploy" to deploy the vault contract.

### Interact with Contracts:

Once deployed, interact with the contracts via the provided functions:
- Connect your EVM Subnet to Remix for executing transactions seamlessly.

## Authors

- **Sarthak**

## License:

This project is licensed under the MIT License. Please refer to the LICENSE file for detailed information.
