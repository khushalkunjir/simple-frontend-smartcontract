# simple-frontend-smartcontract


## Install npm 

## Install http-server 

`npm install -g http-server` 

## Clone the repository 

`git clone https://github.com/khushalkunjir/simple-frontend-smartcontract.git`

## Steps to Deploy and run smart contract

1. Complile the smart contract in REMIX IDE
2. Copy the ABI (At Solidity compiler section -> if scroll down you will find the button ABI)
3. Now When deploying select Enviroment as a Injected provider Metamaks (Make sure you should have some ethers in wallet)
4. Metamask mask will open automatically and confirm the transaction (After confirming wait for 2 mins it will take time to execute)
5. After successfull deployment copy the contract address
6. paste this contract address in html file and contract ABI
   
   ## Example:
   
   ![image](https://github.com/user-attachments/assets/1cbfe0bd-9a0e-4f76-987e-859247f1f8eb)

8. Run the html file with below command
   
   `http-server .`
   
