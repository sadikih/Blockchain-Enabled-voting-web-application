# Blockchain-Enabled Voting Web Application

A decentralized web application built to provide a secure, transparent, and tamper-proof voting system leveraging blockchain technology.

## 🚀 Features
- User registration & login system
- Secure voting process with blockchain-backed immutability
- Real-time vote tallying with transparency
- Privacy-focused architecture to protect voter identity
- Admin panel for managing elections

## 🛠️ Tech Stack
- **Frontend:** Flutter/Dart (for mobile/web interface)
- **Backend:** Node.js / Express.js
- **Blockchain:** Ethereum (Solidity smart contracts)
- **Database:** PostgreSQL
- **Version Control:** Git & GitHub

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blockchain-voting-app.git
   cd blockchain-voting-app
   ```

2. Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```

3. Install frontend dependencies:
   ```bash
   cd frontend
   flutter pub get
   ```

4. Set up PostgreSQL and configure environment variables in `.env`:
   ```env
   DB_HOST=localhost
   DB_USER=postgres
   DB_PASS=yourpassword
   DB_NAME=votingdb
   ```

5. Deploy the smart contract (using Hardhat or Truffle):
   ```bash
   npx hardhat run scripts/deploy.js --network localhost
   ```

6. Start the backend server:
   ```bash
   npm start
   ```

7. Run the frontend app:
   ```bash
   flutter run
   ```

## 🔒 Security
- Blockchain ensures immutability of votes
- Encrypted voter credentials
- Role-based access control (admin & users)

## 📊 Future Improvements
- Multi-election support
- Integration with national ID system for verification
- Mobile money integration for accessibility

---

Made with ❤️ by Sadiki Hamisi
