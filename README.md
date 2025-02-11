# 🚀 AnonChain: Decentralized Anonymous Social Network

## 🌟 Project Goal  
Build a **blockchain-based anonymous social media platform** where users can post messages without revealing their identity.

---

## 🛠️ Tech Stack  
- **Solidity** (Smart Contracts)  
- **Foundry** (Testing)  
- **IPFS** (Decentralized Storage)  
- **zk-SNARKs** (Anonymous Identity Verification)  
- **Hardhat** (Development & Deployment)  
- **React + Web3.js** (Frontend)  

---

## 📌 Progress Log  

📅 **Feb 05** → Completed **8 lessons** in blockchain basics from Cyfrin. 🎯 Target: Finish the remaining lessons tomorrow and wrap up blockchain basics!  
📅 **Feb 06** → Had a meeting with DSW on **boycott FC**, didn't get much done. 😞 Will complete blockchain basics tomorrow. Hope **Tanu** stays safe and focuses on her studies. 🙏  
📅 **Feb 07** → Learning about **Proof of Work (PoW) & Proof of Stake (PoS)**. See explanation below. 🔥  

---

# 🔍 Understanding Proof of Work vs. Proof of Stake

Let's imagine a **pizza restaurant** where customers place orders (transactions) and the restaurant staff processes these orders (validates transactions). 🍕

## 🍕 Scenario 1: Proof of Work (PoW) - The Old System

### **How It Works:**
- Many chefs (**miners**) compete to prepare each pizza (**block**).
- To bake a pizza, they must **solve a puzzle** (do hard work, like kneading tough dough).
- The first chef to finish gets to bake the pizza and **earns a reward + customer tips (gas fees)**.
- Other chefs wasted time and energy competing but got **nothing**. 😞

### **Problems in PoW:**
❌ **Wastes energy** – Many chefs work on the same pizza, but only one gets paid.  
❌ **Slow service** – Only a few pizzas can be made per hour.  
❌ **Expensive** – Chefs need special ovens (**high-end mining computers**).  

---

## 🍕 Scenario 2: Proof of Stake (PoS) - The New System

### **How It Works:**
- Instead of making all chefs compete, the restaurant **chooses one chef at random** to make the pizza.
- To qualify, chefs must **pay a deposit (stake ETH)**.
- A chef is randomly picked to bake the pizza and gets **paid + customer tips (gas fees)**.
- If the chef makes a bad pizza (tries to cheat), the restaurant **takes away their deposit**. ❌

### **Benefits of PoS:**
✅ **No wasted effort** – Only one chef works on each pizza.  
✅ **Faster service** – More pizzas (**transactions**) are made quickly.  
✅ **Lower cost** – No need for expensive ovens (**high-powered mining rigs**).  

---

## ⛽ How Miners/Validators Earn ETH from Gas Fees?

Let’s say customers are ordering pizzas:
- Every order has a **base fee** (burned pizza crust - no one eats it).
- Customers can also leave a **tip** for faster service. 💰

### **In Proof of Work (PoW) - Before Ethereum 2.0:**
- The fastest chef to solve the dough puzzle gets **the tip + pizza price**.
- Other chefs get nothing. ❌

### **In Proof of Stake (PoS) - After Ethereum 2.0:**
- A chef is randomly selected to bake the pizza and gets **the tip + pizza price**.
- Part of the pizza (**base fee**) **is burned** to reduce extra ETH supply. 🔥

---

## 🥇 Summary of PoW vs. PoS

| Feature            | Proof of Work (PoW) 🍕 | Proof of Stake (PoS) 🍕 |
|--------------------|----------------------|----------------------|
| **Who cooks?** | Chefs compete | One chef is randomly chosen |
| **How to qualify?** | Solve a dough puzzle | Pay a deposit (stake ETH) |
| **How is ETH earned?** | Winner gets rewards + tips | Chosen chef gets rewards + tips |
| **Efficiency?** | Wastes energy | Uses only what's needed |
| **Speed?** | Slow | Fast |
| **Cost?** | High (requires special ovens) | Low (anyone with ingredients can join) |

---

### 🍕 Why Ethereum Switched from PoW to PoS?  
1️⃣ **Less energy waste** – No useless kneading of dough.  
2️⃣ **Faster transactions** – More pizzas can be served.  
3️⃣ **Fairer earnings** – No need for expensive ovens (**mining rigs**).  
4️⃣ **ETH supply control** – Some pizza crust (**base fee**) is burned to prevent inflation. 🔥

---

Feb - 08 => Today I have created a wallet on Meta Mask and did my first transaction using sepolia test net which i got some from tenderly.co
one step closer to build AnonChain.

---
Feb - 09 => **How does a block chain actually work ?**

## **1. The Blockchain as a Tamper-Proof Notebook 📖**  
Imagine a **notebook** where people write financial transactions. Each page in the notebook is a **block**, and every page is linked to the previous one, forming a **chain** of pages.  

**Key Takeaways:**  
- **Block** = A page in the notebook  
- **Blockchain** = The entire notebook  
- **Immutable** = If someone tries to erase a page, the ink is permanent!  

---

## **2. How Transactions Work – Sending Money Like Passing Notes 🏦**  
Imagine a classroom where students pass notes (money transfers) to each other. The teacher (a network of computers) verifies if each note is signed properly.  

### **Steps:**  
1. **You Write a Note (Transaction Creation) 📜**  
   - You write: "Alice pays Bob $10" and sign it.  
   - Your signature (private key) ensures only you can authorize the note.  

2. **Teacher Checks the Note (Transaction Verification) ✅**  
   - The teacher (nodes) checks your handwriting (public key verification).  
   - They confirm you actually have $10 before approving.  

3. **Note Goes on the Board (Transaction is Recorded) 📌**  
   - If the note is valid, it gets pinned to a classroom notice board (blockchain).  
   - Once posted, it **can’t be erased or changed**—everyone sees it forever!  

---

## **3. Mining – Solving a Puzzle to Earn Rewards 🏆**  
Think of mining as a **school quiz competition** where students (miners) race to solve a tough math problem. Whoever solves it first gets to **write the next page (block) in the notebook** and wins a **prize (newly minted coins + transaction fees).**  

### **Steps:**  
1. **The Question (Proof-of-Work)**  
   - The teacher gives a super difficult math puzzle.  
   - All students (miners) try random answers until someone gets it right.  

2. **First Correct Answer Wins (Nonce Solved) 🥇**  
   - The first student (miner) to solve it gets to write the next page (block).  
   - They also earn a reward (Bitcoin or Ethereum rewards).  

3. **Other Students Check the Answer (Block Validation) 👀**  
   - The class checks if the answer is correct.  
   - If valid, the page (block) is added permanently.  

> **Why is it Hard?**  
> It prevents cheating—if anyone tries to write false transactions, they’d need to solve the puzzle before others, which is nearly impossible!  

---

## **4. Public-Key Cryptography – Digital Lock & Key 🔐**  
Imagine you have a special mailbox 🏤 where people can send letters (money), but only **you** have the key to open it.  

- **Public Key** = The mailbox address (anyone can see it and send you funds).  
- **Private Key** = Your unique key (only you can use it to unlock and spend money).  

> If someone steals your **private key**, they can take all your money—just like losing your real-life ATM PIN! 😨  

---

## **5. Hashing – The Fingerprint of Data 🆔**  
Imagine you take a **selfie** and apply a filter that creates a unique **fingerprint-like number** (hash). Even a tiny change in the image (data) creates a completely different fingerprint!  

- **Hash (SHA-256)** ensures every block has a **unique fingerprint**.  
- If someone changes anything in a block, its fingerprint changes, breaking the chain!  

---

## **6. Merkle Tree – Organizing Transactions Like a Tournament Bracket 🌳**  
Imagine a **tournament bracket** where players (transactions) compete, and their winners move up until there's a final champion (Merkle Root).  

- The **Merkle Root** summarizes all transactions in a block, making it easy to verify whether a transaction exists without checking the whole block!  

---

## **7. Consensus – The Classroom Voting System 🗳️**  
Imagine a class votes to decide who the best student is.  
- If more than **51%** of students agree (Proof-of-Work/Proof-of-Stake), then the decision is final.  
- If a **cheating group** tries to manipulate votes, they’d need control of 51% of the class—very hard in a large group!  

---

## **8. Forks – Choosing a Different Path 🚦**  
Imagine a group of friends **arguing about where to go**:  
- **Soft Fork**: They all agree to change the plan slightly but still stick together.  
- **Hard Fork**: They **split into two groups**, following separate paths (like Bitcoin and Bitcoin Cash).  

---

## **9. Layer 2 – Building a Fast Lane on a Busy Highway 🚗💨**  
Imagine a **super busy highway** where every car (transaction) must wait in a traffic jam (slow transactions).  

- **Layer 2 solutions** like the **Lightning Network** or **Rollups** build a **fast lane**, processing small transactions off the main highway and settling them later!  

---

## **10. 51% Attack – A Classroom Takeover 😈**  
Imagine in a school election, if a **single group of students** controls 51% of the votes, they can make **fake votes and manipulate the system**.  

> In blockchain, if someone gets 51% of mining power, they can **double-spend money** or reverse transactions!  

---

## **Final Analogy: Blockchain as a Tamper-Proof History Book 📚**  
Think of blockchain as a **history book** where:  
- **Every page (block) is linked** to the previous one.  
- **Everyone has a copy** (decentralization).  
- **Once written, no page can be changed** (immutability).  

If someone tries to edit a past page, all copies will **immediately detect the fraud!** 🚀  

---

### **TL;DR: Blockchain Simplified**
- **Like a permanent notebook**: Every page (block) is linked to the previous.  
- **Like passing notes in class**: Transactions are verified and recorded.  
- **Like a quiz competition**: Miners solve puzzles to add pages.  
- **Like a mailbox with a lock**: Public key = Address, Private key = Unlocks funds.  
- **Like a voting system**: 51% agreement is needed to confirm blocks.  
- **Like a busy highway**: Layer 2 creates fast lanes for quick transactions.  

---

This is how block chain actually works under hood.
### **Understanding Gas in Blockchain**

Gas in blockchain, especially in Ethereum and similar networks, refers to a unit that measures the computational effort required to execute operations, such as transactions or smart contract execution. Think of it as a fee users must pay to use the blockchain network.

---

### **Analogy 1: Fuel for a Car 🚗⛽**
- Just like a car needs fuel (petrol/diesel) to move, transactions on Ethereum need **gas** to be processed.
- The farther you drive (more complex your transaction), the more fuel (gas) you need.
- The fuel price (gas price in Gwei) depends on network congestion—just like petrol prices rise with demand.

---

### **Analogy 2: Paying for Electricity ⚡**
- Imagine your computer runs on electricity, and different tasks (browsing, gaming, rendering videos) consume different amounts of power.
- Simple tasks like opening a browser use little electricity, but heavy tasks like rendering a 3D animation consume much more.
- Similarly, a basic ETH transfer costs little gas, while executing a complex smart contract (like a DeFi transaction) costs a lot.

---

### **What Real Problem is Gas Solving?**
#### **1. Preventing Spam & Overuse (DDoS Protection)**
- If transactions were free, spammers could flood the network with unlimited useless transactions.
- Gas ensures that every action costs money, making spam attacks expensive.

#### **2. Prioritizing Transactions (Efficient Network Use)**
- When the network is congested, miners/validators prioritize transactions that pay higher gas fees.
- This is similar to toll roads where people who pay more can use express lanes.

#### **3. Paying Miners & Validators (Incentivization)**
- Validators (in Proof of Stake) and miners (in Proof of Work) need incentives to process transactions.
- Gas fees ensure that they are compensated for their work.

---

### **Example: Sending ETH vs. Running a Smart Contract**
| Action | Gas Cost (Estimate) | Why? |
|--------|---------------------|------|
| Sending 1 ETH | ~21,000 gas | Simple operation |
| Deploying a Smart Contract | ~200,000+ gas | Needs computation & storage |
| Swapping tokens on Uniswap | ~150,000+ gas | Involves complex calculations |

---

### **Key Takeaways**
1. **Gas is like fuel**—you need it to run transactions on a blockchain.
2. **Prevents spam** by making transactions costly.
3. **Ensures fair processing** by prioritizing transactions with higher fees.
4. **Pays validators** for securing and maintaining the network.

Would you like a deeper dive into gas estimation and optimization? 🚀
