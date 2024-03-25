# Lease and Rent Management Smart Contract

The Lease and Rent Management smart contract facilitates the creation and management of lease agreements, enabling landlords and tenants to interact securely and transparently on the Ethereum blockchain. This contract provides functionalities for creating leases, paying rent, terminating leases, and refunding security deposits.

## Features

- **Lease Creation:** Allows landlords to create lease agreements with specified details such as monthly rent, security deposit, and lease duration.
- **Rent Payment:** Enables tenants to pay monthly rent securely to the landlord, ensuring timely rent collection.
- **Lease Termination:** Allows tenants to terminate lease agreements, providing flexibility and tenant rights.
- **Security Deposit Refund:** Refunds security deposits to tenants upon lease termination, ensuring fair treatment of tenants.

## Usage

### Prerequisites

- Truffle Suite or Hardhat for development and testing
- Node.js and npm installed

### Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

### Testing

Run the Truffle or Hardhat tests:

```bash
truffle test
# or
npx hardhat test
```

### Deployment

Deploy the smart contract to your desired blockchain network using Truffle or Hardhat.

### Examples

Examples of interacting with the smart contract can be found in the `examples/` directory.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
