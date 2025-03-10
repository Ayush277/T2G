
# StakeFit: Fitness Meets Accountability on Web3 🚀💪

**StakeFit** is your ultimate companion for building strong fitness habits. It’s not just an app—it’s a commitment. By staking money on your fitness goals, StakeFit helps you stay accountable and consistent, while ensuring full transparency through blockchain technology. Whether you're crushing daily fitness challenges or tracking your progress, StakeFit keeps you motivated, on track, and rewarded.

- **Accountability:** Put your money where your goals are.
- **Consistency:** Daily staking mandates to keep you disciplined.
- **Transparency:** On-chain progress with proof and attestation.


Stay motivated, stay fit, and let StakeFit hold you accountable for your fitness journey!

---

## **Features**
- **Stake-to-Motivate:** Stake your money to set fitness goals and earn rewards for completing them—or lose it if you don’t.
- **On-Chain Tracking:** All progress data is securely stored on-chain for immutable proof and attestation.
- **Daily Challenges:** Mandated daily fitness activities keep you consistent.
- **Transparency First:** Utilize blockchain for verifiable fitness progress.
- **Developer Convenience:** Includes a CLI tool to simplify contract ownership management.

---
## **Tech Stack**
- **Smart Contracts:** Solidity, Hardhat
- **Frontend & Backend:** React, TypeScript, Scaffold-ETH 2
- **Blockchain Layer:** Base
- **Attestation Protocol:** [Ethereum Attestation Service (EAS)](https://eas.eth.link)
- **Payment SDK:** Coinbase CDP SDK
- **CLI Tool:** Built using Viem for simplified ownership management.

---

## **Challenges We Overcame**
1. **Attestation Configuration:** Navigating EAS documentation and demos to set up attestations correctly.
2. **Integration Hurdles:** Synchronizing independently developed modules into a seamless application.
3. **Payment Processing:** Troubleshooting external payable functions with Coinbase's CDP SDK (issue raised with Coinbase).
4. **Collaboration:** Strengthened our Git workflow and team coordination for smoother collaboration.
5. **Ownership Management:** Developed a CLI tool to transfer contract ownership efficiently.

---

## **How It Works**
1. **Stake Money:** Set your fitness goal and stake a chosen amount of money.
2. **Hit Your Goals:** Complete your daily or weekly fitness challenges.
3. **Earn Rewards:** Meet your goals and earn bonus rewards. Miss them, and your stake contributes to public funding.
4. **Track Progress:** All fitness records are transparently stored on-chain with attestations for credibility.
5. **Manage Ownership:** Use our CLI tool to quickly transfer contract ownership to your main account.

--- 

## **Future Scope**
1. Expand fitness challenges to include team competitions.
2. Introduce NFT rewards for milestones.
3. Enable social sharing to inspire others.


## **CLI Tool**
We built a **command-line interface (CLI) tool** to simplify the process of managing contract ownership. When a contract is deployed locally, it is owned by the default account generated by the local node. This tool allows you to seamlessly transfer ownership to your desired account without manually interacting with the blockchain. 

**Key Features:**
- Transfers ownership from the local node account to your specified account.
- Built using [Viem](https://viem.sh), ensuring speed and reliability.
- Reduces setup errors and accelerates the deployment process.
- After deploying contract run this command
```bash
git clone https://github.com/dhruv1238/ethToBeDecided.git
cd ethToBeDecided/packages/hardhat
npx hardhat transfer-ownership --contract DEPLOYED_CONTRACT_ADDRESS --new-owner NEW_OWNER_ADDRESS
```

## **Steps to Run**
1. Clone the Repository
```bash
git clone https://github.com/dhruv1238/ethToBeDecided.git
cd ethToBeDecided
```
2. Install Dependencies
```bash
yarn install
```
3. Start the local blockchain
```bash
yarn chain
```
4. Deploy the smart contracts
```bash
yarn deploy
```
5. Start the frontend
```bash
yarn start
```
