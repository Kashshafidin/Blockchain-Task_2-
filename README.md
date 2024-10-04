# Blockchain-Task_2-

# Task 2
# AI Model Marketplace

## Description
AI Model Marketplace is a decentralized application (dApp) built on the Ethereum blockchain that allows users to list, purchase, and rate AI models. The application uses smart contracts to securely manage transactions and model listings, ensuring transparency and trust in the marketplace. Users can easily connect their MetaMask wallets to interact with the marketplace.

## Usage
1. **1 Step**: 
   -Sign in MetaMask
     ```

2. **2 Step**: 
   - Write smart contract in Remix Ide

3. **Install Dependencies**:
   - Connect MetaMask and Remix Ide,then use Ganache

5. **Deploy the Smart Contract**: 
   - Make sure to copy the contract address after deployment.

6. **Update the Contract Address**: 
   - In your JavaScript file, replace the placeholder `YOUR_CONTRACT_ADDRESS_HERE` with the actual address of your deployed smart contract.

7. **Run the Application**: 
   - Use a local server or hosting service to serve your frontend files. You can run a simple HTTP server

8. **Connect Your Wallet**: 
   - Open your browser and navigate to the application. Click on the "Connect Wallet" button to connect your MetaMask wallet. Make sure you are on the Ethereum network (testnet or mainnet, depending on your deployment).

9. **Interact with the Application**:
   - **List a Model**: 
     - Enter the model name and price in the provided fields, then click the "List Model" button to list your model on the marketplace.
   - **Purchase a Model**: 
     - Input the model ID you wish to purchase, and click the "Purchase Model" button to proceed with the transaction.
   - **Rate a Model**: 
     - Provide the model ID and your rating (between 1 and 5), then click the "Rate Model" button to submit your rating.
       
## Frontend Overview
The frontend of the application is built using HTML, CSS, and JavaScript. It provides a user-friendly interface that allows users to interact with the smart contract easily. The application uses Web3.js to communicate with the Ethereum blockchain and handle wallet connections.
