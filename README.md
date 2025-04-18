
# 💱 Trade Finance Application using Hyperledger Fabric

This project explores the digitization of trade finance using **blockchain technology**—specifically, **Hyperledger Fabric**, a permissioned and enterprise-grade distributed ledger framework.

Developed by students from **Meenakshi Sundararajan Engineering College**, the project aims to address challenges in traditional trade finance like **paper-based processes**, **security vulnerabilities**, and **third-party dependencies** by leveraging decentralized technologies.

---

## 📌 Project Title

**Trade Finance Application using Hyperledger Fabric**

---

## 👩‍💻 Authors

- **Pujah B.**
- **Gokilavani S.**  
Department of Information Technology,  
Meenakshi Sundararajan Engineering College, Chennai, India

---

## 📋 Abstract

Trade finance refers to domestic and international transactions associated with trade receivables. This project implements a **blockchain-based solution** that replaces paper-heavy, error-prone processes with a **tamper-proof, decentralized** system using Hyperledger Fabric.

Key components include:
- **Certificate Authority**
- **Channels**
- **Private Data Collections**

---

## 🧠 Technologies & Concepts

- Hyperledger Fabric & Composer
- Smart contracts (Chaincode)
- Blockchain consensus mechanisms:
  - Proof-of-Work (PoW)
  - Historical Weighted Difficulty (HWD-PoW)
- Identity Management & Permissioned Networks
- Smart contract development
- Private blockchains

---

## ⚙️ Experimental Setup

### Ethereum Setup Commands
```bash
# Create Genesis Block
geth --datadir=./data init start.json

# Start Local Ethereum Node (example for Mac)
geth --networkid 999 --ipcpath ~/Library/Ethereum/geth.ipc --rpc --rpcaddr "127.0.0.1" \
--rpcapi="db,eth,net,web3,personal,web3" --rpcport "8545" --datadir=./data --rpccorsdomain "*" console

# Create Account
web3.personal.newAccount("password")

# List Accounts
web3.personal.listAccounts

# Start Miner
miner.start(2)

# Run full end-to-end script
./tradee2e.sh -up
```

---

## 📈 Benefits

- Transparent and tamper-proof trade records
- No third-party intermediaries required
- Improved efficiency in international settlements
- Secure document sharing between authorized participants
- Consensus-based trust mechanism
- Auditable and traceable data flow

---

## 🔬 Experimental Enhancements

### Historical Weighted Difficulty Protocol (HWD-PoW)
An improved method to calculate total blockchain difficulty by factoring miner distribution over prior blocks. Helps deter **51% attacks** and selfish mining.

---

## 🌍 Real-World Applications

- International trade settlements
- Supply chain finance
- Carbon credit trading systems
- Credit guarantee management
- Blockchain-based KYC systems

---

## 🔮 Future Enhancements

- Full-scale decentralized finance (DeFi) integration
- Cross-border interoperability among financial institutions
- Integration with centralized banking systems for hybrid architecture
- Improved analytics for financial forecasting and fraud detection

---

## ✅ Conclusion

Using **Hyperledger Fabric**, trade finance applications can be transformed into **highly secure, blockchain-based systems** that are tamper-resistant, transparent, and efficient. This project demonstrates a robust prototype for a decentralized trade finance ecosystem.

---


## 📚 References

- Ethereum & Hyperledger Documentation
- Kyoto Protocol: Carbon Trading Financial Reports
- Global Blockchain Standards (Linux Foundation)

---

## 📄 License

This project is licensed under the [Apache License 2.0](LICENSE) © 2024 Pujah Balasubramaniam.

---
