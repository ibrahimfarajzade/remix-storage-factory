# Storage Factory

This project contains a set of Solidity contracts demonstrating basic storage functionality. The contracts included are:

1. **SimpleStorage.sol:** A simple storage contract with a single variable to store a favorite number and methods to store and retrieve the value. It also includes functionality to add a person with a favorite number and name.

2. **StorageFactory.sol:** A contract that creates instances of the `SimpleStorage` contract and provides methods to interact with them. It enables the creation of multiple storage instances and storing/retrieving values from each instance.

3. **AddFiveStorage.sol:** A contract that extends the `SimpleStorage` contract and overrides the store function to add 5 to the stored value.