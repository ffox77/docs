# NEO White Paper

A distributed network for the Smart Economy

## NEO design goals: Smart Economy

NEO is the use of block-chain technology and digital identity to digitize assets, the use of smart contracts for digital assets to be self-managed, to achieve "smart economy" with a distributed network.

### Digital Assets

Digital assets are programmable assets that exist in the form of electronic data. With the block chain technology, the digitization of assets can be decentralised, free of intermediaries, trustless, traceable, highly transparent and so on. NEO supports multiple digital assets types at the base layer. Users can register their own assets on the NEO, freely trade and circulation, and prove the connection with physical assets through digital identity. The assets registered by the user through a validated digital identity are protected by law.

NEO has two forms of digital assets: global assets and contract assets. Global assets can be recorded in the system space and can be identified by all smart contracts and clients. Contract assets are recorded in the private storage area of ​​the smart contract and requires a compatible client to recognise them. Contract assets can adhere to certain standards in order to achieve compatibility with most clients.

### Digital Identity

Digital identity refers to the identity information of individuals, organizations, and things, that exist in electronic form. The more mature digital identity system is based on the PKI (Public Key Infrastructure) X.509 standard. In NEO, we will implement a set of X.509 compatible digital identity standards. This set of digital identity standards, in addition to compatible X.509 level certificate issuance model, will also support Web Of Trust point-to-point certificate issuance model. Our verification of identity when issuing or using digital identities include the use of facial features, fingerprint, voice, SMS and other multi-factor authentication methods. At the same time, will also use the block chain to replace the OCSP protocol to manage and record the X.509 Certificate Revocation List (CRL).

### Smart Contract

The smart contract was first proposed by the cryptographer Nick Szabo in 1994, almost the same age as the Internet. According to Nick Szabo's definition: When a pre-programmed condition is triggered, the smart contract will execute the corresponding contract terms. Block chain technology provides us with a decentralized, temper-resistant, highly reliable system in which smart contracts are very useful. NEO has an independent smart contract system: NeoContract.

NeoContract smart contract system is the biggest feature of the seamless integration of the existing developer ecosystem. Developers do not need to learn a new programming language but use C#, Java and other mainstream programming languages in their familiar IDE environments (Visual Studio, Eclipse, etc.) for smart contract development, debugging and compilation. NEO's Universal Lightweight Virtual Machine, NeoVM, has the advantages of high certainty, high concurrency, and high scalability. NeoContract smart contract system will allow millions of developers around the world to quickly carry out the development of smart contracts. NeoContract will have a separate white paper describing the implementation details.

### Application and Ecosystem

Ecosystem is the vitality of the open source community. In order to achieve the goal of intelligent economic network, NEO will be committed to the development of ecosystem, provide mature development tools, improve development of documents, organize education and training activities, to provide financial support. We plan to support the following NEO-based applications and ecology and to reward the design of the improvement and improvement experience:

🔹 **Node Program**

- A fully functioning Full node PC program

- A light node PC program with a better user experience

- Web / Android / iOS clients that do not need to synchronize with the blockchain

- Hardware wallet


🔹 **Blockchain Explorer**

🔹 **SDK Development Kit**

- support Java / Kotlin, .NET C # / VB, JavaScript / Typescript, Python, Go

🔹 **Smart Contract Compiler and IDE Plugin**

- C# / VB.Net / F#, Visual Studio

- Java / Kotlin, Eclipse

- C / C++ / GO

- JavaScript / TypeScript

- Python / Ruby

🔹 **Decentralised Applications**

- Smart Fund

- AI-assisted legal smart contract

- Social networking

- Automated tokens liquidity providers

- Decentralised exchange

- Secure communication protocol

- Data exchange market

- IP trading market

- Prediction market

- Advertising market

- Hashpower market

- NeoGas market

## NEO Management Model

### Economic Model

NEO has two native tokens, NEO (abbreviated NEO) and NeoGas (abbreviated symbol GAS).

NEO, with a total of 100 million tokens, represents the right to manage the network. Management rights include voting for bookkeeping, NEO network parameter changes, and so on. The minimum unit of NEO is 1 and can not be divided.

GAS is the fuel token for the realization of NEO network resource control, with maximum total limit of 100 million. The NEO network charges for the operation and storage of tokens and smart contracts, thereby creating economic incentives for bookkeepers and preventing the abuse of resources. The minimum unit of GAS is 0.00000001.

In the creation block of the NEO network, 100 million NEOs are generated, GAS has not yet been generated. 100 million GAS, corresponding to the 100 million NEO, will be generated through a decay algorithm in about 22 years time to address holding NEO. If NEO is transferred to a new address, the subsequent GAS generated will be credited to the new address.

The NEO network will set a threshold by voting to exempt GAS from a certain amount of transfer transactions and smart contract operations to enhance the user experience. When a large amount of spam transactions occur, NeoID can be used to prioritize transactions and smart contracts with qualified identities. Transactions and smart contracts with no qualifying digital identities can get priority by paying GAS.

### Distribution Mechanism

NEO distribution:

NEO's 100 million tokens is divided into two portions. The first portion is 50 million tokens distributed proportionally to supporters of NEO during the crowdfunding. This portion has been distributed.

The second portion is 50 million NEO managed by the NEO Council to support NEO's long-term development, operation and maintenance and ecosystem. The NEO in this portion has a lockout period of 1 year and is unlocked only after October 16, 2017. This portion will not enter the exchanges and is only for long-term support of NEO projects. The plans for it are as below:

🔹 10 million tokens (10% total) are used to motivate NEO developers and members of the NEO Council

🔹 10 million tokens (10% total) are used to motivate developers in the NEO ecosystem

🔹 15 million tokens (15% total) are used to cross-invest in other block-chain projects, which are owned by the NEO Council and are used only for NEO projects

🔹 15 million (total 15%) for buffer

🔹 The annual use of NEO in principle shall not exceed 15 million tokens

GAS distribution:

GAS is generated with each new block. The initial total amount of GAS is zero.With the increasing rate of new block generation, total limit of 100 million GAS will be achieved in about 22 years. NEO The interval between each block is about 15-20 seconds, and 2 million blocks are generated in about one year.

The first year (actually 0-2 million blocks), each block will generate 8 new GAS; the second year (actually the first 2-4 million blocks), each new block will generate 7 GAS and so on. There is annual reduction of 1 GAS for the first 8 years until 1 GAS per block is reached; this will be the rate of GAS generation until about 22 years, after the 44 millionth block, GAS total will reach 100 million, thus stopping the generation of GAS from new blocks.

According to this release curve, 16% of the GAS will be created in the first year, 52% of the GAS will be created in the first four years, and 80% of the GAS will be created in the first 12 years. These GAS will be distributed proportionally in accordance with the NEO holding ratio, recorded in the corresponding addresses. NEO holders can initiate a claim transaction at any time and claim these GAS tokens at their holding addresses.

### Governance mechanism

Chain governance: NEO token holders are the network owners and managers, managing the network through voting in the network, using the GAS generated from NEO to utilise the functions in the network. NEO tokens can be transferred.

Off-chain governance: NEO Council consists of the founding members of the NEO project, under which the management committee, technical committee and the Secretariat, respectively, are responsible for strategic decision-making, technical decision-making and specific implementation. The NEO Council is responsible to the NEO community for the promotion and development of NEO ecosystem as its primary objective.

## NEO technology implementation

### Consensus mechanism: DBFT

DBFT is called the Delegated Byzantine Fault Tolerant, a Byzantine fault-tolerant consensus mechanism that enables large-scale participation in consensus through proxy voting. The holder of the NEO token can, by voting, pick up the bookkeeper it supports. The selected group of bookkeepers, through BFT algorithm, reach a consensus and generate new blocks. Voting in the NEO network continues in real time, rather than in accordance with a fixed term.

DBFT provides fault tolerance of f = ⌊ (n-1) / 3 ⌋ for a consensus system consisting of n consensus nodes. This fault tolerance also includes both security and availability, resistance to general and Byzantine failures, and is suitable for any network environment. DBFT has a good finality, meaning that confirmations are final, the block can not be bifurcated, the transaction will not be revoked or rollback.

In the NEO DBFT consensus mechanism, taking about 15 to 20 seconds to generate a block, the transaction throughput is measured up to about 1000tps, which is excellent performance among the public chains. Through appropriate optimization, there is potential to reach 10,000TPS, allowing it to support large-scale commercial applications.

DBFT combines digital identity technology, meaning the bookkeepers can be a real name of the individual or institution. Thus it is possible to freeze, revoke, inherit, retrieve, and effect judicial decisionson them. This facilitates the registration of compliant financial assets in the NEO network. The NEO network plans to support such operations when necessary.

### Smart contract system: NeoContract

NEO's smart contract system consists of three parts:

**NeoVM - Universal Block Chain Virtual Machine:**

NeoVM is a lightweight, general-purpose virtual machine whose architecture is very close to the JVM and .NET Runtime, similar to a virtual CPU that reads and executes instructions in the contract in sequence, performs process control based on the functionality of the instruction operations, logic operations and so on. It has a good start-up speed and versatility, is very suitable for small programs such as smart contracts, can also be ported to non-block chain of the scene, or integrated with the IDE to provide an optimal development experience. NeoVM's functionality can be extended, like introducing JIT (real-time compiler) mechanism, thereby enhancing the efficiency of the implementation.

**InteropService - Interoperable Services:**

Used to load the blockchain ledger, digital assets, digital identity, persistent storage area and other underlying services. They are like virtual machines that are provided for virtual machines, enabling smart contracts to access these services at run time to achieve some advanced functionality. Through this low-coupling design, **NeoVM can be ported to any block chain or even non-block chain system used, increasing the utility of the smart contracts.**

**DevPack - Compiler and IDE plugin:**

DevPack includes the high-level language compiler and the IDE plug-in. Because NeoVM's architecture is highly similar to the JVM, .NET Runtime, these compilers in DevPack can compile Java byte code and .NET MSIL into NeoVM's instruction set. Java / Kotlin, C# developers do not need to learn new languages and will be able to immediately start developing smart contracts in VS, Eclipse and other familiar IDE environment. **This makes the learning curve of smart contracts greatly reduced, allowing us to easily build a vibrant community around NeoContract.**

NeoContract can create a smart contract call tree through static analysis before running a smart contract. **Through the deterministic call tree, the NEO node can dynamically fragment the smart contract to achieve theoretically unlimited expansion**, which overcomes the "jamming effect" caused by the static fragmentation of other block chain systems.

### Cross-chain interoperability agreement: NeoX

NeoX is a protocol that implements cross-chain interoperability. NeoX is divided into two parts: "cross-chain asset exchange protocol" and "cross-chain distributed transaction protocol."

**Cross-chain asset exchange agreement:**

NeoX has been extended on existing double-stranded atomic asset exchange protocols to allow multiple participants to exchange assets across different chain and to ensure that all steps in the entire transaction process succeed or fail together. In order to achieve this function, we need to use NeoContract function to create a contract account for each participant. For other block chains, if it is not compatible with NeoContact, it can be compatible with NeoX as long as it can provide simple smart contract functionality.

**Cross-chain distributed transaction protocol:**

Cross-chain distributed transactions mean that multiple steps of a transaction are scattered across different block chains and that the consistency of the entire transaction is ensured. This is an extension of cross-chain asset exchange, extending the behavior of asset exchange into arbitrary behavior. In layman's terms, NeoX makes it possible for cross-chain smart contracts where a smart contract can perform different parts on multiple different chain chains, either succeeding or reverting as a whole. This gives great possibilites for cross chain collaborations and we are exploring cross-chain smart contract application scenarios.

### Distributed Storage Protocol: NeoFS

NeoFS is a distributed storage protocol that utilizes Distributed Hash Table technology. NeoFS indexes the data through file content (Hash) rather than file path (URI). Large files will be divided into fixed-size data blocks that are distributed and stored in many different nodes.

The main problem with this type of system is the need to find a balance between redundancy and reliability. NeoFS plans to solve this contradiction by means of tokens incentives and the establishment of backbone nodes. Users can choose the reliability requirements of the file. Files with low reliability requirments can be stored and accessed for free or almost free. high reliability requirements will be provided by the stable and reliable backbone nodes.

NeoFS will serve as one of the InteropService interoperability services under the NeoContract system, enabling smart contracts to store large files on the block chain and set access for those files. In addition, NeoFS can be combined with digital identity so that digital certificates used by digital identities can be assigned, sent, and revoked without a central server to manage. In the future, the old block data can be stored in NeoFS, so that most of the full nodes can release the old data for better scalability and at the same time, ensure the integrity of historical data.

### Anti-quantum cryptography mechanism: NeoQS

The emergence of quantum computers will have a major challenge to RSA and ECC-based cryptographic mechanisms. Quantum computers can solve the large number of decomposition problems that RSA relies on and the elliptic curve discrete logarithm that ECC relies on in a very short time. NeoQS is a lattice-based cryptographic mechanism, and QS is an abbreviation for Quantum Safe. At present, quantum computers do not have the ability to quickly solve the shortest vector problem (SVP) and the recent vector problem (CVP), which is considered to be the most reliable algorithm for resisting quantum computers.

## Summary

NEO is a distributed network that combines digital assets, digital identities and smart contracts. NEO system will also use DBFT, NeoX, NeoFS, NeoQS and many other original technology, as the infrastructure for intelligent economy in the future.