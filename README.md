Security Evaluation of Unverified ERC20 Token Contracts in the Ethereum Blockchain

This study evaluates the security of unverified ERC20 token contracts in the Ethereum blockchain using several popular security analysis tools. The dataset contains smart contract data for ERC20 tokens in SmartContractsData.xls, which includes the results of various security evaluations and analyses.

We utilized four widely-recognized security analysis tools to scan the unverified ERC20 token contracts: HoneyBadger, Maian, Mythril, and SmartBugs. To set up the necessary environment for running these tools, we configured a Docker environment by pulling the latest Docker images of HoneyBadger, Maian, Mythril, and SmartBugs. Each Docker container was set up with the required dependencies, including Python, Solidity compiler Solc, Z3 theorem prover, Web3 library, Go Ethereum client Geth, and other libraries necessary for accurate and error-free execution of these tools.

HoneyBadger: https://github.com/christoftorres/HoneyBadger
Maian: https://github.com/ivicanikolicsg/MAIAN
Mythril: https://github.com/ConsenSys/mythril
SmartBugs: https://github.com/ethereum/SmartBugs
The scan results and analysis data from these tools for each unverified ERC20 contract are stored in the ScanResults folder for further examination and comparison.
