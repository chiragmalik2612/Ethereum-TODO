##Ethereum To-Do List

This project is a decentralized To-Do List application built on the Ethereum blockchain. It allows users to create tasks and mark them as done. The tasks are stored on the blockchain, ensuring immutability and transparency.

![project_image](https://github.com/Himani2615/Ethereum-TODO/assets/143219485/75856521-e2a4-4e7a-a574-577c8d971f5e)


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This is a simple DApp (Decentralized Application) that lets you manage a to-do list on the Ethereum blockchain. It demonstrates basic blockchain and smart contract principles using Solidity, with a web interface for interaction.


## Features

- Create new tasks
- Mark tasks as done

## Technologies Used

- Solidity
- Ethereum
- Truffle
- Web3.js
- Ganache (for local development)

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js and npm
- Truffle (`npm install -g truffle`)
- Ganache (for local blockchain development)
- MetaMask extension for your web browser

## Installation

1. **Clone the repository**
    ```sh
    git clone https://github.com/chiragmalik2612/ethereum-todo-list.git
    cd ethereum-todo-list
    ```

2. **Install dependencies**
    ```sh
    npm install
    ```

3. **Compile the smart contract**
    ```sh
    truffle compile
    ```

4. **Migrate the smart contract to the blockchain**
    Make sure Ganache is running, then:
    ```sh
    truffle migrate --reset
    ```

5. **Start the development server**
    ```sh
    npm run dev
    ```

## Usage

1. **Connect to MetaMask**
    Open your web browser and connect MetaMask to the local blockchain provided by Ganache.

2. **Interact with the To-Do List**
    Open `http://localhost:3000` in your browser. You can now add tasks and mark them as done. All changes will be recorded on the Ethereum blockchain.


## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the repository**
    ```sh
    git fork https://github.com/chiragmalik2612/Ethereum-TODO.git
    ```

2. **Clone your fork**
    ```sh
    git clone https://github.com/chiragmalik2612/Ethereum-TODO.git
    cd eth-todo-list
    ```

3. **Create a new branch for your feature**
    ```sh
    git checkout -b <branchname>
    ```

4. **Make your changes and commit them**
    ```sh
    git add .
    git commit -m 'Add some AmazingFeature'
    ```

5. **Push to your forked repository**
    ```sh
    git push origin feature/AmazingFeature
    ```

6. **Open a pull request**
    Go to the original repository on GitHub and open a pull request with a description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
