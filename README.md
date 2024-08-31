# 📢 PublicFeedback Extension for Scaffold-ETH 2

[![YouTube Video](https://img.youtube.com/vi/O3uNjGznY9U/0.jpg)](https://www.youtube.com/watch?v=O3uNjGznY9U)


## 📝 Introduction

The `PublicFeedback` is a Scaffold-ETH 2 extension designed to facilitate rapid development and iteration through a decentralized feedback mechanism. This extension allows developers to quickly integrate a feedback system into their dApps, enabling secure, transparent, and tamper-proof feedback collection directly on the blockchain.

## 🔑 Key Features

- **Create Feedback Surveys**: Set up new surveys quickly to gather user insights on various topics.
- **Participate in Feedback**: Allow users to provide feedback securely, with all input stored immutably on the blockchain.
- **View Feedback Results**: Access feedback data in real-time on-chain, promoting transparency and open discussion.

## ❓ Why Use PublicFeedbackContract?

In the fast-paced environment of blockchain development, getting timely feedback is crucial for improvement and iteration. The `PublicFeedback` aligns with the Build Guild philosophy of "ship it and reiterate," allowing developers to deploy quickly, gather immediate feedback, and iterate on their projects efficiently.

## 💡 Use Cases

- **Community Engagement**: Actively involve your community in decision-making by soliciting their feedback on key issues.
- **Product Development**: Gather user feedback to prioritize features and enhance your product based on real user needs.
- **Customer Satisfaction**: Continuously improve your offerings by collecting direct input from your users.

## ⚙️ Technical Details

The `PublicFeedback` extension includes a Solidity smart contract and a front-end interface built using Scaffold-ETH 2. It is designed to be fully compatible with the Scaffold-ETH 2 CLI, ensuring easy integration into your projects.

### 🔐 Smart Contract

The Solidity smart contract handles the creation of feedback surveys, recording of user feedback, and storage of results on the blockchain. It ensures that all data is immutable and verifiable, promoting trust and transparency.

### 💻 Front-End Integration

The front-end interface allows developers to easily interact with the contract, creating surveys, submitting feedback, and viewing results. It leverages the power of Scaffold-ETH 2 to provide a seamless developer experience.

## 🚀 Installation and Setup

To get started with the `PublicFeedback` extension, follow these steps:

1. **Create a New Project**: Start by creating a new Scaffold-ETH 2 project using the following command:

    ```bash
    npx create-eth@latest -e 0xcracka/Public-Feedback
    ```

2. **Update the Deployment Script**: Open the `deploy_polling_contract.ts` file, located in the `packages/hardhat/scripts` directory. On line 26, replace the placeholder address with your front-end wallet address. This step is crucial because it sets your wallet address as the contract owner, which is important for controlling who has permission to create polls. By default, the contract is designed to allow only the owner to write to polls, ensuring secure and managed feedback collection. However, if you wish to enable anyone to create polls, you can easily modify the smart contract code to adjust this permission.

## 🛠️ Support

If you encounter any issues or have questions while using the `PublicFeedback` extension, please open an issue on the GitHub repository. Alternatively, feel free to reach out to me directly—I'm here to help!
