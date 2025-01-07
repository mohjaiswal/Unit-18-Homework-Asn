##############################################################################
#                                                                            #
#                            PyChain Ledger                                  #
#                                                                            #
#                     Secure. Decentralized. Efficient.                      #
#                                                                            #
##############################################################################

-------------------------------------------------------------------------------
🔗 A secure, decentralized ledger system for financial transactions
🌐 Built with Python & Streamlit
🔒 Featuring proof-of-work consensus
📊 Real-time blockchain validation
-------------------------------------------------------------------------------
![alt=""](Images/application-image.png)

## Description

PyChain Ledger is a blockchain-based ledger system with a user-friendly web interface built using Python and Streamlit. This system allows for secure recording and verification of financial transactions through a decentralized ledger implementation.

## Features

- Blockchain-based ledger system
- Web-based user interface using Streamlit
- Transaction recording with sender, receiver, and amount
- Proof of work consensus mechanism
- Block validation system
- Block inspection capabilities
- Adjustable mining difficulty

## Technical Architecture

The project consists of several key components:

- `Record` data class for transaction data
- `Block` data class for blockchain structure
- `PyChain` class for chain management
- Streamlit interface for user interaction

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/pychain-ledger.git

# Install required packages
pip install -r requirements.txt

# Required packages:
# - streamlit
# - pandas
# - hashlib
```

## Usage

1. Navigate to the project directory:
```bash
cd pychain-ledger
```

2. Run the Streamlit application:
```bash
streamlit run pychain.py
```

3. Use the web interface to:
   - Enter transaction details (sender, receiver, amount)
   - Add blocks to the chain
   - Inspect blocks
   - Validate the blockchain
   - Adjust mining difficulty

## Technical Components

### Record Data Class
- Stores transaction information
- Attributes: sender, receiver, amount

### Block Data Class
- Contains transaction records
- Includes: timestamp, creator ID, previous hash, nonce
- Implements hash calculation

### PyChain Class
- Manages the blockchain
- Implements proof of work
- Handles chain validation

## Testing

To test the system:
1. Launch the Streamlit interface
2. Add multiple transactions
3. Verify block contents in the dropdown menu
4. Test blockchain validation
5. Adjust difficulty and observe mining impact

## Support

For support:
- Open an issue in the GitHub repository
- Contact: your.email@example.com

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to the branch
5. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Project Status

Active development - Version 1.0.0

## Acknowledgments

- Streamlit documentation
- Python blockchain community
- Course instructors and peers

---

## Disclaimer

This is an educational project demonstrating blockchain concepts. It should not be used for production-level financial transactions without proper security auditing and improvements.
