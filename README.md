# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

How to run the project in Remix:-

Add parameter tokenSupply in Token.sol and then deploy it.
Add parameter token address of Token.sol in VotingToken.sol file and then deploy it.
After deploying both files you have to transfer some tokens to the VotingToken.sol contract address from Token.sol tranfer function.
Now the owner can open the voting for people by passing the deadline parameter.
Users can buy the token by using the Buy function.
After buying the token user can vote to the candidate.
Owner can check the votes candidates got.
If the deadline will end voting will close automatically.
Or the Owner can also close the voting.