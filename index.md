---
layout: default
title: DataMatch - The Future of Data Transactions
---

# DataMatch - The Future of Data Transactions  

**Aditya Melkote, Maxwell Fang, Yanhao Guo, Zixin Wei**  
**Mentor: Sheffield Nolan**  
📧 avmelkote@ucsd.edu, m3fang@ucsd.edu, yag007@ucsd.edu, z5wei@ucsd.edu, Sheffield.Nolan@franklintempleton.com  

---

## Abstract  
Data scientists require vast amounts of data to train models. **Current data marketplaces** expose users to **privacy risks, high costs, and security vulnerabilities**.  

💡 **DataMatch** is a decentralized, Ethereum-based data marketplace that allows users to **buy and sell datasets securely, without intermediaries**.  

**Key Features:**  
✅ **Smart contracts** for automated transactions and licensing  
✅ **Personally Identifiable Information (PII) Removal** for privacy  
✅ **InterPlanetary File System (IPFS)** for secure, off-chain storage  
✅ **Blockchain-based marketplace** ensuring trustless interactions  

🔗 **[GitHub Repository](https://github.com/Fangtastic7/DSC-180B-B16--Group1)**  

---

## 1. Introduction  
Data is one of the most valuable assets in the digital economy. However, **current online data marketplaces** are:  
🚨 **Prone to security breaches** (e.g., UnitedHealthcare data hack in 2024)  
💰 **Expensive**, requiring **hefty transaction fees**  
⚠️ **Centralized**, leading to **single-point failures**  

**Why Blockchain?**  
Blockchain provides **a decentralized, immutable, and secure** alternative for **data transactions**. Ethereum smart contracts enable **trustless data exchanges** while ensuring **user privacy** through cryptographic techniques.

**Why IPFS?**  
Since blockchains struggle with **scalability**, we store datasets **off-chain in IPFS**, a **peer-to-peer decentralized storage network** that **protects against data leaks and tampering**.

---

## 2. Overview  
Our project builds a **secure, trustless, and scalable data marketplace** by integrating:  
🛡️ **Ethereum-based smart contracts** for transparency  
📂 **IPFS storage** to eliminate central failure points  
🔒 **PII Removal** to ensure privacy  
💱 **MetaMask integration** for seamless transactions  

**How It Works:**  
1️⃣ **Sellers list datasets**, which are **encrypted and uploaded to IPFS**  
2️⃣ **Smart contracts handle transactions** securely  
3️⃣ **Buyers purchase access** to the dataset using MetaMask  
4️⃣ **Datasets remain secure & accessible** via cryptographic keys  

🌟 **Smart contracts automate** licensing, payments, and access control, making DataMatch a **secure and decentralized alternative** to traditional data markets.

---

## 3. Literature Review  
Many decentralized marketplace proposals exist, but they **struggle with usability, privacy, and scalability**.  

🔹 **Sober et al. (2022)**: Blockchain-based IoT data trading reduces **trust issues** but lacks privacy features.  
🔹 **Fonseca et al. (2020)**: Swarm-based decentralized storage enhances **scalability**, but data retrieval is inefficient.  
🔹 **da Silva Vanin et al. (2022)**: Homomorphic encryption enables **privacy-preserving data processing**.  
🔹 **Li et al. (2020)**: Blockchain-based licensing provides **automated, transparent ownership records**.  

Our solution **combines these advancements** to create a **secure, scalable, and privacy-preserving marketplace**.

---

## 4. Infrastructure  

### **4.1 Core Technologies**  
✅ **Smart Contract Development (Remix IDE, Ethereum, Amoy Testnet)**  
✅ **Wallet Integration (MetaMask for Transactions)**  
✅ **Data Storage (Amazon S3, Pinata, IPFS)**  
✅ **Frontend & Backend (Next.js, Ethers.js)**  
✅ **NLP-Based PII Removal (spaCy for Entity Detection)**  

### **4.2 How the System Works**  
1️⃣ **Seller uploads dataset** → PII **detected and removed**  
2️⃣ **Encrypted dataset stored on IPFS via Pinata**  
3️⃣ **Smart contract records the dataset, pricing, and permissions**  
4️⃣ **Buyer purchases dataset using MetaMask**  
5️⃣ **Dataset remains secure, preventing unauthorized downloads**  

🌍 **Decentralization ensures** data is protected **even if a single storage provider fails**.

---

## 5. Methods  

### **5.1 Smart Contract Functionality**  
- `listData()`: Seller lists dataset (automatically encrypts & removes PII)  
- `buyData()`: Buyer purchases dataset (transaction confirmed via blockchain)  
- `delistData()`: Seller removes dataset from marketplace  
- `getInventory()`: Buyer accesses purchased datasets  

⚙️ **All transactions are immutable and recorded transparently on the Ethereum blockchain**.

### **5.2 PII Removal Process**  
🔍 **spaCy NLP** detects:  
- Names  
- Email addresses  
- Phone numbers  
- Any other personally identifiable information  

🛡️ **Sanitized datasets** are stored **only after PII is removed**.

### **5.3 IPFS Integration**  
📡 **Pinata uploads datasets** to IPFS, which returns a **unique CID (Content Identifier)**.  
🔗 **CID is stored on the blockchain** and used to retrieve files securely.  

---

## 6. User Interaction  

### **6.1 Buying Data**  
1️⃣ **User logs into MetaMask** and browses datasets.  
2️⃣ **Click "Buy"**, triggering a smart contract transaction.  
3️⃣ **Dataset access granted** via blockchain authentication.  
4️⃣ **User retrieves dataset** securely using the **IPFS CID**.  

### **6.2 Selling Data**  
1️⃣ **Seller uploads dataset** (PII removed, encrypted).  
2️⃣ **File stored in IPFS**, CID recorded on blockchain.  
3️⃣ **Listing appears on marketplace** for buyers.  
4️⃣ **Smart contract manages** transactions securely.  

🌟 **Transactions are automatic, eliminating intermediaries!**  

---

## 7. Future Work  
🚀 **Planned Enhancements:**  
🔹 **Improve market interface** for better usability  
🔹 **Recommendation algorithm** to help users find relevant datasets  
🔹 **Token incentives** for high-quality data contributions  
🔹 **Advanced encryption techniques** for stronger security  

---

## 8. Acknowledgements  
We sincerely thank:  
🎓 **Sheffield Nolan (Mentor)**  
📚 **Professor Bellur**  
🛠️ **TA Aritra Das** for their guidance and support  

🔗 **[Visit Our Live Website](#)**  

---

## 9. References  
📖 Fonseca, J., Dahal, B., & Kim, Y. (2020). Decentralized Marketplace Using Blockchain.  
📖 Li, J. et al. (2020). Blockchain-Based Educational Digital Assets Management.  
📖 da Silva Vanin, F. et al. (2022). Blockchain-Based Data Protection Model.  
📖 Sober, M. et al. (2022). Blockchain-Based IoT Data Marketplace.  
