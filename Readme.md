# Task 2
# AI Model Marketplace

## Description
AI Model Marketplace is a decentralized application (dApp) built on the Ethereum blockchain that allows users to list, purchase, and rate AI models. The application uses smart contracts to securely manage transactions and model listings, ensuring transparency and trust in the marketplace. Users can easily connect their MetaMask wallets to interact with the marketplace.

## Usage
1. **Clone the Repository**: 
   - Open your terminal and run the following command to clone the repository to your local machine:
     ```bash
     git clone https://github.com/yourusername/AIModelMarketplace.git
     ```

2. **Navigate to the Project Directory**: 
   - Change into the project directory:
     ```bash
     cd AIModelMarketplace
     ```

3. **Install Dependencies**: 
   - Ensure you have Node.js and npm installed. Then, install the necessary dependencies by running:
     ```bash
     npm install
     ```

4. **Deploy the Smart Contract**: 
   - Use Remix or your preferred development environment to deploy the smart contract. Make sure to copy the contract address after deployment.

5. **Update the Contract Address**: 
   - In your JavaScript file, replace the placeholder `YOUR_CONTRACT_ADDRESS_HERE` with the actual address of your deployed smart contract.

6. **Run the Application**: 
   - Use a local server or hosting service to serve your frontend files. You can run a simple HTTP server using:
     ```bash
     npx http-server .
     ```

7. **Connect Your Wallet**: 
   - Open your browser and navigate to the application. Click on the "Connect Wallet" button to connect your MetaMask wallet. Make sure you are on the Ethereum network (testnet or mainnet, depending on your deployment).

8. **Interact with the Application**:
   - **List a Model**: 
     - Enter the model name and price in the provided fields, then click the "List Model" button to list your model on the marketplace.
   - **Purchase a Model**: 
     - Input the model ID you wish to purchase, and click the "Purchase Model" button to proceed with the transaction.
   - **Rate a Model**: 
     - Provide the model ID and your rating (between 1 and 5), then click the "Rate Model" button to submit your rating.

## Demo Screenshots
*Include your demo screenshots here. These images showcase the functionality of the application, such as the model listing interface, purchase interface, and rating system.*

## Smart Contract Code
The smart contract for the AI Model Marketplace handles the logic for listing, purchasing, and rating AI models. It includes functions to manage model data and ensure that transactions are executed securely.

## Frontend Overview
The frontend of the application is built using HTML, CSS, and JavaScript. It provides a user-friendly interface that allows users to interact with the smart contract easily. The application uses Web3.js to communicate with the Ethereum blockchain and handle wallet connections.

## License
This project is licensed under the MIT License. For more details, please refer to the LICENSE file in the repository.

