# EHR-LockChain

<!-- Project Intro -->

<div align="center">
  <img src="./readme-data/ehr-logo-main.png" width="150" height="150" />

<h3 align="center">A <span style="color:#197ae0;">decentralized</span> EHR data management system</h3>

<p align="center">
    A decentralized application (dApp) that runs it's backend on a decentralized server, i.e. <a href="https://ethereum.org/en/">Ethereum blockchain</a>.
    <br />
    <span >Patients can use the application to manage sharing and access control of their medical records with respective doctors registered on application<span>
    <br />
  </p>
</div>

## About

The project provides a secure and decentralized application designed to store and manage electronic health records (EHRs). Leveraging the power of the Ethereum blockchain, smart contracts, Interplanetary File System (IPFS) and hybrid encryption, the application provides patients with complete control over their medical data, while ensuring that their records remain secure and private.

With the application, patients can easily grant and revoke access to doctors as needed. Our decentralized access control system ensures that only the autorized parties can view and edit medical records, while also ensuring that patients maintain control over their own data.

### Advantage over traditional systems

While today's traditional EHR systems store data and manage access control through a centralized server in healthcare centers, users have to trust these organizations and their trust-based contracts for security of their data.

Our system takes a different approach. With our platform, both storage and access control is decentralized and transparent. The application executes in a trustless and verifiable environment powered by smart contracts on Ethereum blockchain where users can see the code of contract managing the access control and can view exactly how the data is stored on distributed IPFS network. In addition to distributed storage, the encryption and decryption of data is done using the user's own public and private key pairs so none other than user and his trusted parties can decrypt the data.

## Technologies Used

[HTML][html-url] [Javascript][javascript-url] [NextJS][nextjs-url] [Mantine][mantine-url] [Wagmi][wagmi-url] [Metamask][metamask-url] [Ethereum][ethereum-url] [Solidity][solidity-url] [Hardhat][hardhat-url] [Ethers][ethers-url]

#### Folder structure

- `utils/` contains all pure functions, these functions take some parameters, does some computation, and returns the result, depends on pre-built modules like `crypto`, `web3.storage`, `@metamask/eth-sig-util`.
- `hooks/` contains all communication functions (custom react hooks) used for communicating between frontend, backend and IPFS. These hooks use functions in `utils/`.
- `components/` contains all UI components and handles UI and user interaction. Built using [Mantine.dev](https://mantine.dev/) UI library, and depends on custom react hooks in `/frontend/hooks` to display dynamic data.
- `pages/` contains routes of application that users can visit. A single page combines one or more componets from `components/`.

### Installation

1. **Install Dependencies**:
   ```bash
   npm install
   ```
3. **Run the Development Server**:
   ```bash
   npm run dev
   ```

<!-- Links -->

[html]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[html-url]: https://developer.mozilla.org/en-US/docs/Web/HTML
[bootstrap]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[bootstrap-url]: https://getbootstrap.com/docs/5.0/getting-started/introduction/
[javascript]: https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
[javascript-url]: https://www.javascript.com/
[ethereum]: https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white
[ethereum-url]: https://ethereum.org/en/
[chainlink]: https://img.shields.io/badge/chainlink-375BD2?style=for-the-badge&logo=chainlink&logoColor=white
[chainlink-url]: https://chain.link/
[solidity]: https://img.shields.io/static/v1?label=&message=Solidity&color=dodgerblue&style=for-the-badge&logo=hardhat
[solidity-url]: https://docs.soliditylang.org/
[hardhat]: https://img.shields.io/static/v1?label=&message=Hardhat&color=yellow&style=for-the-badge&logo=hardhat
[hardhat-url]: https://hardhat.org/
[ethers.js]: https://img.shields.io/static/v1?label=&message=Ethers.js&color=royalblue&style=for-the-badge&logo=hardhat
[ethers-url]: https://docs.ethers.io/v5/
[wagmi]: https://img.shields.io/static/v1?label=&message=Wagmi&color=black&style=for-the-badge&logo=wagmi
[wagmi-url]: https://wagmi.sh/
[nextjs]: https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white
[nextjs-url]: https://nextjs.org/
[mantine]: https://img.shields.io/static/v1?label=&message=Mantine&color=blue&style=for-the-badge&logo=mantine
[mantine-url]: https://mantine.dev/
[metamask]: https://img.shields.io/static/v1?label=&message=Metamask&color=orange&style=for-the-badge&logo=metamask
[metamask-url]: https://metamask.io/
