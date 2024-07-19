# EpicChain Testnet

## Requirements

To set up and run the EpicChain Testnet, you will need the following tools and software:

- **[Docker](https://www.docker.com/get-started)**: Docker is required for containerization and managing the EpicChain Testnet environment. Ensure that Docker is installed and configured on your system.
- **[Docker Compose](https://docs.docker.com/compose/)**: Docker Compose is used to define and run multi-container Docker applications. Install Docker Compose to manage the various components of the EpicChain Testnet.

## EpicChain Local Setup

The EpicChain local setup includes the following components:

**Contains:**
- **EpicChain Storage Nodes**: 10 nodes are set up to handle storage tasks within the testnet environment.
- **EpicChain Inner Ring Nodes**: 4 nodes dedicated to maintaining the internal network's connectivity and consensus.
- **EpicChain HTTP Gateway**: Accessible at [localhost:7000](http://localhost:7000), this gateway provides an interface for interacting with the EpicChain network.
- **EpicChain Drop (Send.EpicChain)**: Available at [localhost:7001](http://localhost:7001), this component allows for the transfer of data and assets within the EpicChain ecosystem.
- **EpicChain CLI**: A command-line interface for managing and interacting with the EpicChain Testnet.
- **EpicChain Private Network**: The private network configuration for testing and development purposes.
- **Nginx**: A web server used for serving static content and acting as a reverse proxy for the EpicChain components.

For detailed instructions and setup guidance, refer to the [**How to**](./epicchain-local/HOWTO.md) document. This guide will help you with configuration, deployment, and management of the EpicChain Testnet.

## Problems / Issues?

If you encounter any problems or issues with the EpicChain Testnet setup, please [**submit an issue**](https://github.com/epicchain-dev/epicchain-local/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5BBUG%5D) on our GitHub repository. Provide as much detail as possible to help us diagnose and resolve any issues you may be facing.

Our team is committed to maintaining and improving the EpicChain Testnet, and your feedback is crucial for its success. We appreciate your contributions and look forward to addressing any concerns you might have.

