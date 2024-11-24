# Embark: Revolutionizing Web3 Education and Onboarding

## Problem Embark Solves

Embark addresses critical challenges in the Web3 and DAO (Decentralized Autonomous Organization) landscape, providing innovative solutions to ease user adoption, learning, and decision-making:

### **1. Embark on Seamless Onboarding**
- **Challenge:** Onboarding into the Web3 space can be overwhelming due to complex documentation and tutorials.
- **Solution:** Embark simplifies the process by enabling direct connections between new users and experienced DAO delegates through decentralized video calls. This offers a swift, hassle-free introduction to Web3.

### **2. Embark on Real-Time Learning**
- **Challenge:** Understanding Web3 and DAO concepts can be difficult without direct, personalized guidance.
- **Solution:** Using Huddle01, users can join live one-on-one or group sessions during DAO delegates' office hours. They receive personalized support, ask questions, and deepen their knowledge in real-time.

### **3. Embark on Empowered Decision-Making**
- **Challenge:** Many users lack the tools or knowledge to participate effectively in DAO governance and decision-making.
- **Solution:** Embark empowers users to delegate their voting power effortlessly. Users can engage with trusted delegates during educational sessions, actively participating in DAO decisions.

### **4. Embark on On-Chain Recognition**
- **Challenge:** There's often no formal recognition for educational contributions within DAOs.
- **Solution:** Embark allows the creation of on-chain NFTs that represent a delegate's educational contributions. These NFTs enhance a delegate’s reputation score, ensuring fair recognition and potentially unlocking rewards within the DAO.

### **5. Embark on AI-Enhanced Support**
- **Challenge:** Educational support often ends when a live session finishes.
- **Solution:** Embark integrates AI-powered chatbots, using meeting transcripts to offer continuous support and information, ensuring a holistic learning experience even when delegates are unavailable.

## Challenges We Ran Into

### **1. Finding the Right APIs**
The first challenge was sourcing APIs to access DAO data. Each DAO has its own inconsistent API structure, making it difficult to standardize and interact with them efficiently. We overcame this by integrating multiple DAO-specific APIs and normalizing the data.

### **2. Finding the Right AI Model**
Another challenge was selecting an AI model to transcribe meetings and enable users to interact with the transcripted data. After extensive research and testing, we found a suitable model and fine-tuned it to serve our purpose effectively.

### **3. Managing Meeting Data with Huddle01**
Handling meeting data on the server-side posed a technical challenge, especially with Huddle01’s integration. However, by leveraging blockchain-based Solidity contracts and React.js, we were able to devise an effective solution to save and manage meeting data securely.

## Installation

```bash
# Clone the repository
git clone <repository-url>

# Install dependencies
npm install

# Start the development server
npm run dev
