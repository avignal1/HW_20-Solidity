# Associate Profit Splitter

## Smart Contract
- Goal is to deploy a contract that will accept ether and divide evenly among associate level employees

Step 1) Defining Public Variables
![Public Variables](Screenshots/PublicVariables.PNG)

Step 2) Creating Constructor that Accepts Payable Addresses
![Constructor](Screenshots/Constructor.PNG)

Step 3) Balance Function
    - already defined by StarterCode

Step 4) Deposit Function
![Deposit](Screenshots/DepositFunction.PNG)
    - Uses Global Variables "msg.sender" and "msg.value"

Step 5) External Payable Function
![External Payable](Screenshots/ExternalPayableFunction.PNG)

## Deploying Contract
    1. Enviornment set to "Injected Web3" to connect to LocalHost in MetaMax
    2. Initial value set to 0 wei
    3. Addresses taken from Ganache

![Deploying Contract](Screenshots/DeployingContract.PNG)

![Pre-Transaction Amounts ](Screenshots/PreTransactionAmounts.PNG)

## Completing Transaction