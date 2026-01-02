The contract has an owner, who will act as the administrator of the voting process.

The owner is automatically set to the address that deploys the contract using msg.sender.

Here,only the owner has the power to control the status of the contract i.e. Voting is on or voting is off.

The last line is performed by the contract checks whether the address is the owner or not.

If any regular(non-owner) tries to start or stop voting, the transaction fails with an error,they can only perform voting function only once.

This ownership logic ensures that the voting process is controlled, fair, and protected from unauthorized access.
