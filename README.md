# â›“ï¸ Vanguard Core

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Technology: Blockchain](https://img.shields.io/badge/tech-blockchain-purple.svg)](#)

**Vanguard Core** is a lightweight, modular blockchain implementation written in Python. It provides the essential building blocks for understanding and experimenting with Distributed Ledger Technology (DLT), including Proof-of-Work (PoW) consensus, block mining, and transaction management.

## ðŸš€ Features
- **Proof-of-Work Consensus:** Adjustable difficulty for mining blocks.
- **Immutable Ledger:** Cryptographic linking of blocks using SHA-256.
- **Modular Design:** Simple classes for Blocks and the Blockchain.
- **Transaction Pool:** Management of unconfirmed transactions before mining.

## ðŸ› ï¸ Quick Start
```python
from vanguard_core import Blockchain

# Initialize the blockchain
vanguard = Blockchain(difficulty=3)

# Add transactions
vanguard.add_new_transaction({"sender": "Alice", "receiver": "Bob", "amount": 50})

# Mine a block
vanguard.mine()

# Check the chain
print(f"Current chain length: {len(vanguard.chain)}")
print(f"Latest Block Hash: {vanguard.last_block.hash}")
```

## ðŸ¤ Contributing
Interested in decentralization? Feel free to open issues or submit PRs to improve the core logic or add networking capabilities.

---
Built with âš¡ by [David Selorm Walker](https://github.com/selormwalker)
