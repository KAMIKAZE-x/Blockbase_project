# On-Chain Expense Tracker DApp

A decentralized application (DApp) for tracking and splitting expenses among users, built on the Ethereum blockchain. This project allows users to register, add expenses, and settle debts in a transparent and immutable way.

## Application Screenshots and Features Demonstration

### 1. Main Interface and Currency Conversion
![Main Interface](screenshots/main-interface.png)

This screenshot demonstrates the main interface of the application with the following features:
- Connected wallet address: 0x8b55C4a7f7d7E88dF063dd0FA0f938D280cd6509
- ETH/INR currency conversion toggle button
- Current ETH to INR exchange rate display (1 ETH = ₹139,138)
- Welcome message with user's registered name
- Total registered users counter
- "Get My Registered Name" functionality
- Add Expense and Refresh Expenses options

### 2. Smart Contract Transaction
![Transaction Details](screenshots/transaction-details.png)

This screenshot shows a successful transaction on the Sepolia testnet:
- Transaction Hash: 0xcf7ad467fc117ff652cfd849b724c23b02ca2eb5c57987ab333ccf36831ec2b9
- Status: Success with 2 Block Confirmations
- Block: 8163206
- Contract Interaction: Method call to the expense tracker contract
- Gas Usage and Transaction Details
- Timestamp: Apr-21-2025 04:45:48 AM UTC

### 3. Expense Management
![Expense Management](screenshots/expense-management.png)

The expense management interface shows:
- New expense creation form titled "New Expense"
- Sample expense entry "shopping"
- Multiple participant entries with:
  - Wallet addresses
  - Amount paid
  - Amount owed
  - Remove participant option
- Add Participant and Save Expense buttons
- People section showing registered users and their balances

### 4. Expense History
![Expense History](screenshots/expense-history.png)

The expense history view displays:
1. Travel Expense:
   - Date: 4/21/2025, 9:52:36 AM
   - Participant: Saksham Ojha
   - Paid: 3232.0 ETH (₹449694016.00)
   - Owes: 595.0 ETH (₹82787110.00)

2. Shopping Expense:
   - Date: 4/21/2025, 10:15:48 AM
   - Multiple participants
   - Each entry showing:
     - Paid: 12.0 ETH (₹1669656.00)
     - Owes: 8.0 ETH (₹1113104.00)

These screenshots demonstrate the complete functionality of the expense tracker DApp, showcasing its ability to handle wallet connections, expense management, transaction processing, and dual-currency display features.

## Features

### Core Features
1. **User Registration**
   - Register with your Ethereum wallet
   - Set your display name
   - View registration status

2. **Expense Management**
   - Add new expenses with multiple participants
   - Track who paid and who owes
   - View expense history
   - See detailed breakdown of each expense

3. **Balance Tracking**
   - View net balances for all users
   - Track who owes whom
   - Color-coded display (red for debts, green for credits)

### Enhanced Features

1. **User Information Display**
   - View connected wallet address
   - Check registration status
   - Get your registered name
   - See total number of registered users
   - View last expense label

2. **Currency Conversion**
   - Toggle between ETH and INR display
   - Real-time ETH/INR price updates
   - Automatic price refresh every 5 minutes
   - Clear display of amounts in both currencies

3. **Smart Contract Features**
   - Check if a user is registered
   - Get total number of registered users
   - Get label of the last expense
   - Get your own registered name
   - View detailed expense information

## Technical Details

### Smart Contract
- Written in Solidity
- Deployed on Ethereum network
- Contract Address: `0x1B2bc323feB1e1B0ba347573724c234A1c7ef8b9`

### Frontend
- Built with React.js
- Uses ethers.js for blockchain interaction
- Real-time price updates from CoinGecko API
- Responsive UI with clear data visualization

## Getting Started

1. **Prerequisites**
   - MetaMask or similar Ethereum wallet
   - Node.js and npm installed
   - Ethereum testnet (Sepolia) configured in wallet

2. **Installation**
   ```bash
   npm install
   npm start
   ```

3. **Usage**
   - Connect your Ethereum wallet
   - Register with your name
   - Start adding expenses
   - View balances and settle debts
   - Toggle between ETH and INR display

## Development

### Project Structure
- `src/BlockBase.sol`: Smart contract code
- `src/App.js`: Main React application
- `src/ExpenseTrackerABI.json`: Contract ABI

### Available Scripts
- `npm start`: Runs the app in development mode
- `npm test`: Launches the test runner
- `npm run build`: Builds the app for production

## Contributing
Feel free to submit issues and enhancement requests!

## License
This project is licensed under the MIT License.
