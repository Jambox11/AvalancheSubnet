# Creating an EVM-Subnet on Avalanche

## Overview
This project establishes an EVM Subnet on the Avalanche network named "JamesSubnet," featuring its native token, GamersTokens (JAM). The network seamlessly integrates with MetaMask, enabling the deployment and interaction with smart contracts through the injected provider on Remix.

## Project Features
This project interacts with two smart contracts: an ERC20 token and a vault contract. These contracts support the following functionalities:

- **Token Creation**: Deploy your own ERC-20 token with customizable details such as name, symbol, and decimals.
- **Token Transfers**: Users can transfer tokens to other addresses with ease, following the widely adopted ERC-20 standard.
- **Token Minting**: The contract owner has the ability to mint new tokens, expanding the total token supply.
- **Token Burning**: Users can burn their own tokens, reducing the overall token supply.

## Getting Started
Follow these steps to get the project up and running on your local machine.

### Prerequisites
- Node.js and npm installed on your machine.

### Installing
1. Clone the repository using the command:
   ```sh
   git clone https://github.com/username/projectname.git
   ```
Change directory into your project file:
  ```sh
  cd projectname
   ```
Install all dependencies:
  ```sh
  npm install
   ```
Executing Program
Compile the contract using Hardhat:
  ```sh
  npx hardhat compile
   ```
Run the deployment script:
  ```sh
  npx hardhat run scripts/deploy.js
   ```
### Tools Used
Unix Computer (MacOS or Linux)
Solidity
Remix/Hardhat
Metamask
Web Browser
### Author
James Akolo
### License
This project is licensed under the [jambox] License - see the LICENSE.md file for details.
