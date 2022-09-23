# Naive_receiver
Challenge 2 of damn-vulnerable defi using Foundry framework

# Basic idea
There is a pool initilized by naiveReceiver contract , and the utilities like flashLoan function is provided by the LenderPool contract.

What we only do is just recursively call the flashLoan function to drain all the ETH in it .

# Forge test
In order to forge test our exploit , just use command ```forge test --match-test testExploit ```  , and it will pass .
