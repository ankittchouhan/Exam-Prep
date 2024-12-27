### **11. Explain the Working and Applications of SHA-256**

#### **Definition**:  
SHA-256 (Secure Hash Algorithm 256-bit) is a cryptographic hash function that takes an input and generates a 256-bit (64-character) fixed-length string, irrespective of the input size. It is widely used for its strong security and resistance to tampering.

#### **Working of SHA-256**:  
1. **Input Data**: Any type of data (text, file, etc.) can be given as input.  
2. **Pre-Processing**: The data is padded to ensure its length is a multiple of 512 bits.  
3. **Message Compression**: The padded data is divided into 512-bit chunks.  
4. **Hash Calculation**: Each chunk undergoes a series of logical operations, including bitwise shifts, rotations, and modular additions.  
5. **Output Hash**: The final output is a unique 256-bit fixed-length hash value.

#### **Applications of SHA-256**:  
- **Blockchain**: Ensures data integrity and secures transactions.  
- **Digital Signatures**: Verifies the authenticity of data.  
- **Password Protection**: Safeguards stored passwords.  
- **Certificate Validation**: Used in SSL certificates for secure communication.  

---

### **12. Explain the Working and Applications of MD5**

#### **Definition**:  
MD5 (Message Digest Algorithm 5) is a cryptographic hash function that produces a 128-bit (32-character) fixed-length hash value from any input. It is fast but less secure compared to modern algorithms like SHA-256.

#### **Working of MD5**:  
1. **Input Data**: The input is processed in 512-bit blocks.  
2. **Padding**: The input is padded to ensure its length is a multiple of 512 bits.  
3. **Hash Calculation**: Logical operations (AND, OR, XOR) are performed in four main rounds.  
4. **Output Hash**: A 128-bit hash is generated as the final output.

#### **Applications of MD5**:  
- **File Integrity**: Verifies that files haven’t been tampered with.  
- **Checksum Generation**: Ensures data accuracy during transfers.  
- **Digital Watermarking**: Adds lightweight protection to digital content.  
- **Non-Critical Applications**: Suitable for applications that don’t require high security.  

---

### **13. Explain the Challenges and Limitations of Smart Contracts**

#### **Definition**:  
A **Smart Contract** is a self-executing contract with predefined terms written into code. It automatically enforces and executes the terms without the need for intermediaries.

#### **Challenges and Limitations**:  
1. **Security Vulnerabilities**: Bugs or coding errors can be exploited by attackers.  
2. **Lack of Legal Clarity**: Many jurisdictions do not recognize smart contracts as legally binding.  
3. **Scalability Issues**: High demand on blockchain networks can slow execution.  
4. **Immutability**: Once deployed, the code cannot be modified, even if errors exist.  
5. **Resource Limitation**: Smart contracts have limited access to external data and computation.  
6. **Cost**: Deployment and execution involve gas fees, which can be high during network congestion.  
7. **Complexity**: Creating secure and efficient smart contracts requires specialized knowledge.  

---

### **14. Define Smart Contract. What Are the Key Features of Smart Contract?**

#### **Definition**:  
A **Smart Contract** is a digital agreement executed automatically on a blockchain. It contains the terms of the agreement in code and ensures that the agreement is enforced without intermediaries.

#### **Key Features**:  
1. **Automation**: Executes automatically when predefined conditions are met.  
2. **Transparency**: All participants can view the contract details.  
3. **Immutability**: Once deployed, the contract code cannot be altered.  
4. **Security**: Cryptographic techniques ensure safety from tampering.  
5. **Cost-Efficiency**: Eliminates intermediaries, reducing transaction costs.  
6. **Decentralization**: Operates on a blockchain, ensuring no central authority is needed.  

---

### **15. Explain the Different Types of Consensus Mechanisms**

#### **Definition**:  
A **Consensus Mechanism** is a process by which blockchain participants agree on the validity of transactions and the state of the network. It ensures that all nodes have a consistent copy of the blockchain.

#### **Types of Consensus Mechanisms**:  
1. **Proof of Work (PoW)**:  
   - Miners solve complex mathematical puzzles to validate transactions.  
   - Used in Bitcoin.  
   - Energy-intensive but highly secure.  

2. **Proof of Stake (PoS)**:  
   - Validators are chosen based on their stake (coins held).  
   - Energy-efficient.  
   - Used in Ethereum 2.0.  

3. **Delegated Proof of Stake (DPoS)**:  
   - Stakeholders elect delegates to validate transactions.  
   - Faster than PoS but less decentralized.  

4. **Proof of Authority (PoA)**:  
   - Validators are pre-approved and trustworthy entities.  
   - Used in private blockchains.  

5. **Proof of Elapsed Time (PoET)**:  
   - Validators are chosen based on a fair random wait time.  
   - Used in Hyperledger.  

6. **Byzantine Fault Tolerance (BFT)**:  
   - Handles faulty or malicious nodes while maintaining consensus.  
   - Used in systems like Ripple.  

---

### **16. What Is a Ledger in Blockchain? Explain the Different Types of Ledger**

#### **Definition**:  
A **Ledger** in blockchain is a digital record of all transactions maintained across a decentralized network.

#### **Types of Ledgers**:  
1. **Public Ledger**:  
   - Accessible to anyone.  
   - Example: Bitcoin blockchain.  

2. **Private Ledger**:  
   - Access is restricted to authorized participants.  
   - Example: Company-specific blockchains.

3. **Consortium Ledger**:  
   - Controlled by a group of organizations.  
   - Example: Hyperledger.

4. **Hybrid Ledger**:  
   - Combines features of public and private ledgers.  
   - Example: Ripple.

---

### **17. Explain the Importance and Key Features of a Ledger in Blockchain**

#### **Importance of Ledger**:  
- **Transparency**: Everyone can verify transactions (in public ledgers).  
- **Immutability**: Once recorded, data cannot be altered.  
- **Decentralization**: No central authority is required.  
- **Security**: Cryptographic techniques ensure tamper-proof records.  

#### **Key Features**:  
1. **Distributed**: Copies of the ledger are stored across multiple nodes.  
2. **Immutable**: Past records cannot be changed.  
3. **Real-Time Updates**: Transactions are recorded instantly.  
4. **Auditability**: Transaction history is easily traceable.  
5. **Resilience**: Even if some nodes fail, the ledger remains operational.

---

### **18. What Is Bitcoin? How Are Bitcoin Coins Created?**

#### **Definition**:  
Bitcoin is a digital currency operating on a decentralized blockchain network. It enables peer-to-peer transactions without the need for intermediaries.

#### **How Bitcoins Are Created**:  
- **Mining**:  
  - Miners solve mathematical puzzles using computational power.  
  - Successful miners add a block to the blockchain and are rewarded with new bitcoins.  
- **Fixed Supply**:  
  - The total supply of bitcoins is capped at 21 million coins.  

---

### **19. What Is Double Spending? How Does Bitcoin Prevent Double Spending?**

#### **Definition**:  
Double Spending occurs when a digital currency is spent more than once, leading to transaction fraud.

#### **How Bitcoin Prevents Double Spending**:  
1. **Blockchain Validation**: Each transaction is recorded in a block and verified by all nodes.  
2. **Consensus Mechanism**: PoW ensures that only valid transactions are added to the blockchain.  
3. **Timestamping**: Transactions are time-stamped and linked sequentially.  
4. **Decentralization**: No single entity can manipulate the transaction record.

---

### **20. What Is Bitcoin Mining? How Does Bitcoin Mining Work?**

#### **Definition**:  
Bitcoin Mining is the process of validating and adding new transactions to the blockchain while generating new bitcoins as rewards.

#### **How Bitcoin Mining Works**:  
1. **Transaction Pool**: New transactions are grouped into a block.  
2. **Solving Puzzles**: Miners solve cryptographic puzzles to validate the block.  
3. **Proof of Work**: The first miner to solve the puzzle broadcasts the block to the network.  
4. **Block Addition**: Once validated by other nodes, the block is added to the blockchain.  
5. **Reward**: The miner receives newly created bitcoins and transaction fees as a reward.  
 
