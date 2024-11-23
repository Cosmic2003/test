# Blockchain Simulator

A Python-based blockchain simulator designed to provide a hands-on experience with the fundamental concepts of blockchain technology. This project serves as an educational tool, enabling users to understand how blockchains operate by simulating key processes such as adding transactions, mining blocks using Proof-of-Work, and verifying the integrity of the chain. It offers an interactive command-line interface for managing transactions, adjusting mining difficulty, and exploring the blockchain's structure. Additionally, the project includes a comprehensive set of test cases built with pytest to ensure the accuracy and reliability of all functionalities, making it suitable for both learning and experimentation.

## Video Demo
URL: [Blockchain Simulation](https://youtu.be/r9TIrMVYebY)

## Description

### Features

- **Blockchain Implementation**:
  - Add transactions
  - Mine blocks with Proof-of-Work
  - Validate the blockchain
  - Calculate account balances
- **Interactive Menu**:
  - Add new transactions
  - Mine pending transactions
  - View the blockchain
  - Check account balances
  - Verify the blockchain's integrity
  - Adjust mining difficulty
- **Testing Suite**: Comprehensive test cases using `pytest` to ensure functionality.

### Project Structure

```plaintext
.
├── project.py          # Contains the blockchain and menu implementation
├── test_project.py     # Test cases for the blockchain functionality
└── requirements.txt    # List of dependencies
```
### Installation

Follow these steps to set up the Blockchain Simulator on your local machine:

1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```
2. **Install Dependency**:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

#### Running the Blockchain Simulator
 Start the simulator by running the following command:
   ```bash
   python project.py
   ```

### Example
#### Adding and Mining Transactions
1. **Add Transactions:**
   - Enter sender, recipient, and the transaction amount.
2. **Mine pending transactions:**
   - Generate a new block to add pending transactions to the chain.
   - Earn a mining reward for your address.
#### Viewing the Blockchain
- Each Block Includes:
    - Index: The block's position in the chain.
    - Timestamp: When the block was mined.
    - Transactions: A list of transactions included in the block.
    - Hash: The unique hash of the block.
    - Previous hash: The hash of the preceding block.
    - Nonce (Proof-of-Work): The number used to solve the cryptographic challenge during mining.
#### Testing Blockchain Integrity
- Verify the blockchain to ensure no tampering has occurred.
#### Technologies Used
- Python: Core programming language.
- pytest: Testing framework for functional validation.
