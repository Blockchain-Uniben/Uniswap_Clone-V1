## uniswapV1_Clone
### A public repo to explore the intricacies of Uniswap Architecture for educational and experimental purposes

Uniswap is a cryptocurrency exchange which uses a decentralized network protocol.
It is an automated liquidity protocol powered by a constant product formula and implemented in a system of non-upgradeable smart contracts on the Ethereum blockchain. It obviates the need for trusted intermediaries, prioritizing decentralization, censorship resistance, and security.

In Uniswap version 1 which will be of focus on this repository, we will be considering the development of two main contracts which formed the basis of the software before it's subsequent updates.

### We will build the;
1. Token Contract
2. Exchange Contract

## Token Contract
Uniswap V1 supports only ether-token swaps. To make that possible we will build an ERC20 token contract for our custom token that will trade against ether. 

## Exchange Contract
The Exchange contract is where all the processing happens, it actually defines exchanging logic. Each pair (eth-token) is deployed as an exchange contract and allows to exchange ether to/from only one token.

It will hold functions for addLiquidity, price, price correction, and swapping algorithms,swap fees, etc.

We will pay close attention to Jewain's works and explanations as he puts it on his repo; https://github.com/Jeiwan/zuniswap

### LFG!!!
