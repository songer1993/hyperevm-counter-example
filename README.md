# Hyperliquid EVM Counter Example

A simple example demonstrating how to deploy and interact with smart contracts on the Hyperliquid EVM testnet.

## Prerequisites

- Python 3.8+
- Web3.py
- Access to Hyperliquid testnet
- Test ETH in your wallet

## Installation
1. Clone the repository:
```shell
git clone https://github.com/songer1993/hyperevm-counter-example.git
cd hyperevm-counter-example
```

2. Install dependencies:
```shell
pip install web3 python-dotenv
```

3. Create a `.env` file in the root directory:
```plaintext
DEPLOYER_PRIVATE_KEY='your_private_key_here'
```

## Contract Details

The project includes a simple Counter smart contract with the following functions:
- `constructor()`: Initializes the counter to 0
- `increment()`: Increments the counter by 1
- `getCount()`: Returns the current count

## Usage

See `counter-example.ipynb` for deployment and testing.

## Project Structure

```plaintext
├── bin/
│   ├── Counter.abi        # Contract ABI
│   └── Counter.bin        # Contract bytecode
├── Counter.sol            # Solidity source code
├── counter-example.ipynb  # Jupyter notebook for deployment and testing
├── README.md             # Project documentation
├── .env                  # Environment variables (not in git)
└── .gitignore           # Git ignore rules
```

## Security

- Never commit your private keys or `.env` file
- Use testnet for development
- Always review transactions before signing

## Network Details

- Network: Hyperliquid Testnet
- RPC URL: https://api.hyperliquid-testnet.xyz/evm

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Hyperliquid team for the testnet
- Web3.py documentation
- Solidity documentation
