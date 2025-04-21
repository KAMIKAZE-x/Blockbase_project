# On-Chain Expense Tracker DApp

A decentralized application (DApp) for tracking and splitting expenses among users, built on the Ethereum blockchain. This project allows users to register, add expenses, and settle debts in a transparent and immutable way.

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
