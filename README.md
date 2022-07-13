# Building-and-using-External-Adapters

Chainlink is an infrastructure designed to be unlimited in how customizable it can be. External adapters are open sourced packages that allows Chainlink nodes to transform and receive data however they like. With external adapters you can do: 
1. API Authentication (keep private API password keys private) 
2. Private, low latency, and/or high throughput off-chain computation to save gas. 
3. Write data to other blockchains (interoperability).
4. Any desired functionality that isn’t covered with the core adapters
This allows your solidity smart contracts to have access to data that they never would have before. 


## Steps
1. git clone https://github.com/thodges-gh/CL-EA-NodeJS-Template.git ExternalAdapterProject
