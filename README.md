## create a account in metamask ##

## At initial stage you dont have ETH value to get ETH value just go for mining   using the bellow link ##
``` https://goerli-faucet.pk910.de/ ```

##  run the ERC20.sol in remix ##

## Open Ethereum scan and verify the contract id creation ##

## ABI code ##
[{"inputs":[{"internalType":"string","name":"name_","type":"string"},{"internalType":"string","name":"symbol_","type":"string"}],"stateMutability":"nonpayable","type":"constructor"},{"anonymous":false,"inputs":[{"indexed":true,"internalType":"address","name":"owner","type":"address"},{"indexed":true,"internalType":"address","name":"spender","type":"address"},{"indexed":false,"internalType":"uint256","name":"value","type":"uint256"}],"name":"Approval","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"internalType":"address","name":"from","type":"address"},{"indexed":true,"internalType":"address","name":"to","type":"address"},{"indexed":false,"internalType":"uint256","name":"value","type":"uint256"}],"name":"Transfer","type":"event"},{"inputs":[{"internalType":"address","name":"owner","type":"address"},{"internalType":"address","name":"spender","type":"address"}],"name":"allowance","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"stateMutability":"view","type":"function"},{"inputs":[{"internalType":"address","name":"spender","type":"address"},{"internalType":"uint256","name":"amount","type":"uint256"}],"name":"approve","outputs":[{"internalType":"bool","name":"","type":"bool"}],"stateMutability":"nonpayable","type":"function"},{"inputs":[{"internalType":"address","name":"account","type":"address"}],"name":"balanceOf","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"stateMutability":"view","type":"function"},{"inputs":[],"name":"decimals","outputs":[{"internalType":"uint8","name":"","type":"uint8"}],"stateMutability":"view","type":"function"},{"inputs":[{"internalType":"address","name":"spender","type":"address"},{"internalType":"uint256","name":"subtractedValue","type":"uint256"}],"name":"decreaseAllowance","outputs":[{"internalType":"bool","name":"","type":"bool"}],"stateMutability":"nonpayable","type":"function"},{"inputs":[{"internalType":"address","name":"spender","type":"address"},{"internalType":"uint256","name":"addedValue","type":"uint256"}],"name":"increaseAllowance","outputs":[{"internalType":"bool","name":"","type":"bool"}],"stateMutability":"nonpayable","type":"function"},{"inputs":[],"name":"name","outputs":[{"internalType":"string","name":"","type":"string"}],"stateMutability":"view","type":"function"},{"inputs":[],"name":"symbol","outputs":[{"internalType":"string","name":"","type":"string"}],"stateMutability":"view","type":"function"},{"inputs":[],"name":"totalSupply","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"stateMutability":"view","type":"function"},{"inputs":[{"internalType":"address","name":"to","type":"address"},{"internalType":"uint256","name":"amount","type":"uint256"}],"name":"transfer","outputs":[{"internalType":"bool","name":"","type":"bool"}],"stateMutability":"nonpayable","type":"function"},{"inputs":[{"internalType":"address","name":"from","type":"address"},{"internalType":"address","name":"to","type":"address"},{"internalType":"uint256","name":"amount","type":"uint256"}],"name":"transferFrom","outputs":[{"internalType":"bool","name":"","type":"bool"}],"stateMutability":"nonpayable","type":"function"}]

## open visual studio command and copy my code from github and clone in visual studio and follow my Readme file ##

## run python3 webserver.py ##
note: while runing curl command use the port value as 8080 instered of 8090
## and follow the bellow given steps ## 
## Build an Image ##

```docker build --tag blockchain .```


## Run an image ##

```docker run --name blockchain -p 8090:8080 blockchain ```

## Run the curl command ##

This transfers ETH:

```curl --header "Content-Type: application/json" --request POST --data '{"address":"0xb136bF09EE1348933493759e4f24C0b9B2739f42", "amount":"0.05"}' http://localhost:8090/eth```

This transfers token:

```curl --header "Content-Type: application/json" --request POST --data '{"address":"0x3Bf4e37F587E6FBd473a5AE32CF2569b52a9A4C1"}' http://localhost:8090/token```

## the above command is used to send SHB token ##

## install docker ##

## open docker hub and create repo##

## Next step is that push your image in docker following command ##

## command ##
1.docker ps  
2.docker images     
3.dockerr image tag blockchain/kirthikesh/block_chain:latest
4.docker image tag blockchain blockchain/kirthikesh/block_chain:latest
5.docker login -u kirthikesh with password 
6.docker push kirthikesh/block_chain:latest 

## done ##
## then your image will be sended in docker hub ##                                                
## DOCKER PUSH COMMAND ##
```docker pull kirthikesh/block_chain```


## DOCKER PULL COMMAND ##

```docker pull kirthikesh/block_chain```

## Thank You ##

