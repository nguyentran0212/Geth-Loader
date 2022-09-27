# Geth Loader

Use case:
1. You have a data folder backup from a Geth (Go-Ethereum) node of a private blockchain network
2. You want to continue running the blockchain network from that data folder
3. You want to explore the content of the blockchain network stored in that data folder

Geth Loader is a simple utility that helps you start a Geth node with an existing data folder, expose the necessary ports, and run a visual blockchain explorer to browse the transaction.

Under the hood, Geth Loader relies on Docker and Docker compose.