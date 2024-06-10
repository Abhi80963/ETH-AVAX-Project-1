# ETH-AVAX-Project-1

# Crowdfunding Smart Contract

This repository contains a smart contract for a simple crowdfunding platform on the Ethereum blockchain. The contract allows contributors to donate Ether towards a fundraising goal, and ensures that funds are only released to the beneficiary if the goal is met. If the goal is not met and the crowdsale is closed, contributors can get a refund.

## Features

- **Contribution**: Contributors can donate Ether to the crowdfunding campaign.
- **Goal Check**: The contract checks if the fundraising goal has been reached.
- **Crowdsale Closure**: The contract owner can close the crowdsale.
- **Refunds**: Contributors can get a refund if the fundraising goal is not met and the crowdsale is closed.
- **Error Handling**: Uses `require()`, `revert()`, and `assert()` statements for robust error handling.

## Getting Started

### Prerequisites

- [Remix IDE](https://remix.ethereum.org/)

### Installation

1. Open [Remix IDE](https://remix.ethereum.org/).
2. Create a new file and paste the smart contract code into the file.
3. Compile the smart contract using the Solidity compiler in Remix.

### Deployment

1. In Remix, go to the "Deploy & Run Transactions" tab.
2. Select "JavaScript VM" or connect to your preferred Ethereum network (e.g., via MetaMask).
3. Deploy the contract by selecting the compiled contract and clicking the "Deploy" button.

### Usage

1. After deployment, use the deployed contract instance in Remix to interact with the contract.
2. Use the `contribute` function to make contributions.
3. Use the `closeCrowdsale` function to close the crowdsale when you decide to end it.
4. Use the `checkGoalReached` function to transfer funds to the beneficiary if the fundraising goal is met.
5. Use the `refund` function to get a refund if the fundraising goal is not met and the crowdsale is closed.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or enhancements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
