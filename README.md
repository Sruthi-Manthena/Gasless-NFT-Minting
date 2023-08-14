
# Biconomy Gasless NFT Minting

This project demonstrates how to mint an NFT without paying gas fees using Biconomy on the Polygon Mumbai Network. The example code allows users to mint an NFT by leveraging Biconomy's gasless transaction capabilities.

## Prerequisites

- Node.js 
- Private Key for the Ethereum Wallet

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Sruthi-Manthena/Gasless-NFT-Minting
   cd Gasless-NFT-Minting
   ```
2. Install Dependecies
   ```bash
   npm install or yarn install 
   ```
3. Create a .env file in the root directory and add your private key
   ```bash
   PRIVATE_KEY="your-private-key-here"
   ```
4. Replace YOUR_BUNDLER_URL and YOUR_PAYMASTER_URL with the actual URLs from your Biconomy account.
5. Run the script
    ```bash
   npm run dev 
   ``` 

## Explanation
The code provided in index.ts demonstrates the following steps:

* Initialize Biconomy configuration and smart account setup.
* Create a Biconomy smart account and retrieve its address.
* Define a function to mint an NFT using Biconomy's gasless transaction features.
* Prepare the minting transaction and build a user operation.
* Calculate and incorporate gas fee quotes using Biconomy's Paymaster.
* Execute the user operation for gasless NFT minting.


## Resources

- [Biconomy Documentation](https://docs.biconomy.io/)
- [Biconomy GitHub](https://github.com/bcnmy)

