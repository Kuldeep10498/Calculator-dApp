# Calculator
 Beginner friendly demo to build a Calculator dApp on Aptos using Move 
DApp Calculator
Overview
The DApp Calculator is a decentralized application (DApp) built using the Move programming language and the Aptos blockchain. This application allows users to perform basic arithmetic operations like addition, subtraction, multiplication, and division directly on the blockchain, ensuring transparency and immutability.

Features
Basic Arithmetic Operations: Perform addition, subtraction, multiplication, and division.
Decentralization: Built on the Aptos blockchain for secure and transparent calculations.
User-Friendly Interface: Intuitive UI for easy interaction.
Real-Time Results: Instant feedback on calculations.
Tech Stack
Move: A safe and secure programming language for smart contracts.
Aptos: A high-performance blockchain for deploying DApps.
React: For building the user interface (if applicable).
TypeScript: For type safety and better development experience.
License
This project is licensed under the MIT License. See the LICENSE file for details.

## Deploy the Smart Contract
To deploy the smart contract:

Install Aptos CLI.

Update the Move.toml file with your wallet address:

aptos init
Add your Account addr here for Deployment
calculator = "0x558d8ff240a01dbfdbc86b24c46743bbbebcce9319873908355cda2d206b208f"
Compile and publish the contract:

aptos move compile
aptos move publish

Acknowledgments
Aptos for providing a robust blockchain framework.
