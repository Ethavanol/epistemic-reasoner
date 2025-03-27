## Epistemic Reasoner API (Express/Node.js Server)
This is a fork of [Michael Vezina Epistemic Reasonner](https://github.com/MikeVezina/epistemic-reasoner). This server provides a simple API for creating, updating, and reasoning about Explicit Epistemic models. 

## Epistemic Agents
The agents using this reasoner can be found at: https://github.com/Ethavanol/epistemic-agents

# Getting Started
## Prerequisites
Node Version: 16 (Current, found here: https://nodejs.org/en/download/current/).

This API will call another Service written in Python and using the TouIST command line tool.
The TouIST Service and the TouIST tool need to be installed. For this, refer to here : https://github.com/Ethavanol/touist-service

## Setting up the application
### 1. Clone the repository
```
git clone https://github.com/Ethavanol/epistemic-reasoner.git
cd epistemic-reasoner
```

### 2. Install dependencies
```
npm install
```

### 3. Starting the application
```
npm start
```
