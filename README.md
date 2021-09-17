# Cake Defi Staking 


### Dependenies:

[Node.js](https://nodejs.org/en/)

[Ganache(GUI)](https://www.trufflesuite.com/ganache)

[truffle website](https://www.trufflesuite.com/docs/truffle/getting-started/using-truffle-develop-and-the-console)

[truffle installed](https://github.com/trufflesuite/truffle)

[Metamask extension for Google Chrome installed](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en)



### 1. Smart Contract Part:


Ganache panel, import the `truffle-config` file into workspace. Set RPC SERVER as `HTTP://127.0.0.1:7545`

<br/>

Run codes below:
```
truffle console
truffle(development)> compile
truffle(development)> migrate
truffle(development)> test

```
<br/>

If you want to issue tokens, run this code in command line:
```
truffle exec scripts/issue-token.js 
```
 
### 2. Front-end Interfaces Part:

1. Custom rpc in Metamask, new RPC url: `HTTP://127.0.0.1:7545`
2. run codes below:

<br/>

```json
npm install 
npm start 
// open http://localhost:3000/
```



## Go and play defi farming happily!👩‍🌾👨‍🌾, earn your CAKEs