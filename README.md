# Units Network Testnet Bot

This repository contains a Node.js application that automates transactions on the Units Network Testnet using multiple private keys.

## Requirements

- Node.js
- npm (Node Package Manager)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/meysamb95/units-network-bot1.git
   cd units-network-bot1
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Prepare private keys:**

   - Create or edit `privateKeys.json` to include your Ethereum private keys as an array of strings. Each private key should be enclosed in double quotes.

   ```console
   # Edit script
   nano privateKeys.json
   ```

   **Paste the following code and replace `private_key_1_here` with your wallet private key between "" symboles (correct format):**
   ```json
   [
       "private_key_1_here"
   ]
   ```

   **You can add more private keys if you want like this:**
   ```json
   [
       "private_key_1_here",
       "private_key_2_here"
   ]
   ```

   Ensure each private key string is correctly formatted as shown above.


## Usage

- **Run the application:**

  ```bash
  npm start
  ```

- Follow the prompts to enter the number of transactions to send per private key.
