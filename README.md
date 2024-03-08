# Storage Factory

This project contains a set of Solidity contracts demonstrating basic storage functionality. The contracts included are:

1. **SimpleStorage.sol:** A simple storage contract with a single variable to store a favorite number and methods to store and retrieve the value. It also includes functionality to add a person with a favorite number and name.

2. **StorageFactory.sol:** A contract that creates instances of the `SimpleStorage` contract and provides methods to interact with them. It enables the creation of multiple storage instances and storing/retrieving values from each instance.

3. **AddFiveStorage.sol:** A contract that extends the `SimpleStorage` contract and overrides the store function to add 5 to the stored value.

## Getting Started

1. Go to [Remix](https://remix.ethereum.org/)
2. Paste the code from `FundMe.sol` and `PriceConverter.sol` into new files in Remix
3. Hit `Compile`
4. Hit `Deploy`

For a more in depth blog on working with remix, [read here](https://docs.chain.link/docs/deploy-your-first-contract/)

## Smart Contract Details

- **Solidity Version**: 0.8.19
- **License**: MIT

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.