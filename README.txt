# Offchain Data Access with Chainlink Functions

This repository contains two Solidity smart contracts for accessing offchain data using Chainlink Functions oracles. The contracts allow making HTTP requests to retrieve information from the Star Wars API and the weather API.

## Contracts

### 1. GettingStartedFunctionsConsumer.sol

This contract interacts with the Star Wars API through a Chainlink oracle to retrieve information about a character.

### 2. WeatherFunctions.sol

This contract interacts with the weather API through a Chainlink oracle to retrieve the current temperature of a city.

## Usage

### 1. Deploying the Contracts

Before using the contracts, make sure to deploy them on a compatible network. You can use Truffle or another smart contract development framework for deployment.

### 2. Configuring Requests

Before making data requests, ensure that you configure the necessary parameters such as the address of the Chainlink Functions oracle and the subscription ID.

### 3. Making Requests

Once the contracts are deployed and configured, you can make data requests using the functions provided by the contracts. Make sure to provide the required parameters such as the subscription ID and request arguments.

### 4. Interacting with the Response

Once a response is received from the oracle, you can interact with it through the contracts' interface. This may include reading the response stored in public variables or emitting events with the obtained response.

## Additional Resources

- [Chainlink Functions on Fuji](https://functions.chain.link/fuji): Official page for Chainlink Functions on the Fuji test network. Here, you can find additional information on using Chainlink Functions and obtaining test tokens for making requests.

