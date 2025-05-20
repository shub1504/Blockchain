This repository contains practical insights and basic hands-on examples on four key components of blockchain technology:

1. [MetaMask](#1-metamask)
2. [IPFS](#2-ipfs)
3. [Solidity](#3-solidity)
4. [Hyperledger](#4-hyperledger)

---

## 1. 🦊 MetaMask

###  What is MetaMask?
MetaMask is a crypto wallet and gateway to blockchain apps. It allows you to interact with Ethereum-based Apps directly from your browser.

###  Installation Steps:
1. Go to [https://metamask.io/](https://metamask.io/)
2. Download the browser extension (available for Chrome, Firefox, Edge, Brave).
3. Create a wallet or import an existing one using a seed phrase.
4. Connect to Ethereum Mainnet or a testnet (e.g., Ropsten, Goerli).


Account ID : 0x6014aF5Ab46B3041E718f75f5d8C9c8FB9beDd31

![6147792277867710094](https://github.com/user-attachments/assets/f812af83-53d0-4ab4-abe7-4dbb13015054)

---

## 2. IPFS (InterPlanetary File System)

###  What is IPFS?
IPFS is a distributed system for storing and accessing files, websites, and data using peer-to-peer technology.

###  Installation Steps:
1. Visit [https://ipfs.tech/](https://ipfs.tech/)
2. Download and install IPFS Desktop for your OS.
3. Initialize your node and add a file to see how it is stored and accessed using a unique content hash (CID).

### Example:
- Added a text file to IPFS and accessed it via a gateway link like:
  `https://ipfs.io/ipfs/<your-cid>`

![IPFS 3](https://github.com/user-attachments/assets/e0d6475c-d0db-4170-9a00-a33b06ae6bd4)
![IPFS 2](https://github.com/user-attachments/assets/63f2c245-3e6a-4177-8b35-24e92f62e32c)
![IPFS 1](https://github.com/user-attachments/assets/b325cf4d-4d32-400f-93da-28f1b54fb5af)


## 3.  Solidity

###  What is Solidity?
Solidity is a high-level programming language used to write smart contracts for the Ethereum Virtual Machine (EVM).

###  How to Use:
1. Use [Remix IDE](https://remix.ethereum.org/) (online IDE for Solidity).
2. Write and deploy basic smart contracts.
3. Interact with contracts using the Remix UI or MetaMask.

###  Example:
- Wrote a simple "HelloWorld" contract.
- Deployed on Remix with injected Web3 (MetaMask integration).

![solidity](https://github.com/user-attachments/assets/e0c9d030-a4f2-4461-842f-74ca63a65678)

---

## 4.  Hyperledger

###  What is Hyperledger?
Hyperledger is an open-source collaborative project for enterprise blockchain solutions, hosted by The Linux Foundation.

### BASIC COMMANDS TO INSTALL Hyperledger Fabric

1. Make sure you’ve already installed:

2. Go

3. Docker & Docker Compose

4.  Curl

5.  Node.js (for chaincode dev sometimes)

# Step 1: Clone the fabric samples repo
git clone https://github.com/hyperledger/fabric-samples.git

# Step 2: Move into the directory
cd fabric-samples

# Step 3: Run the bootstrap script to download binaries, docker images, and samples
curl -sSL https://bit.ly/HyperledgerFabricInstaller | bash -s

# OR use the official bootstrap script (recommended)
./scripts/bootstrap.sh

# Step 4: Check if everything downloaded
ls bin/


### BASIC COMMANDS TO INSTALL Go (Golang)

# Step 1: Download Go (replace version if needed)
wget https://go.dev/dl/go1.21.0.linux-amd64.tar.gz

# Step 2: Remove older Go version if any
sudo rm -rf /usr/local/go

# Step 3: Extract the tarball to /usr/local
sudo tar -C /usr/local -xzf go1.21.0.linux-amd64.tar.gz

# Step 4: Add Go to PATH (temporary)
export PATH=$PATH:/usr/local/go/bin

# (Optional) Add to ~/.profile or ~/.bashrc for permanent path
echo 'export PATH=$PATH:/usr/local/go/bin' >> ~/.bashrc
source ~/.bashrc

# Step 5: Check if Go installed
go version

![hyper](https://github.com/user-attachments/assets/f85797fd-e845-487f-b66c-d355f0d91411)

![hyper2](https://github.com/user-attachments/assets/7feb5f4f-07ff-4a96-a7cd-0fbc349b2c96)

![hyper3](https://github.com/user-attachments/assets/29948134-3f53-47f2-9605-a1be60708659)

![hyper4](https://github.com/user-attachments/assets/9b972368-a01b-44fb-bbfd-9e864bace578)

![hyper5](https://github.com/user-attachments/assets/73861b96-e296-4a87-976d-2d940687517c)

![hyper6](https://github.com/user-attachments/assets/0c6bd72e-5393-4fad-b1bb-9eacc98ea974)

👉 [Click here to view all Blockchain Practicals](./Blockchain_Practicals.md)







