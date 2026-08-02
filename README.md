# Degen Wars - Browser Artillery Game 2026

> **Degen Wars is a turn-based artillery experience that runs in the browser and connects gameplay systems to Solana through TypeScript, React, Rust, and Anchor.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser%20with%20Solana-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/isaac-brooksvfz684/degen-wars-react-game?style=flat-square)](https://github.com/isaac-brooksvfz684/degen-wars-react-game)

---

<p align="center">
  <a href="https://isaac-brooksvfz684.github.io/degen-wars-react-game/">
    <img src="https://img.shields.io/badge/Download-Degen%20Wars%20Latest-brightgreen?style=for-the-badge" alt="Download Degen Wars">
  </a>
</p>

> **[Download Degen Wars](https://isaac-brooksvfz684.github.io/degen-wars-react-game/)**

---

[Download Latest Build](https://isaac-brooksvfz684.github.io/degen-wars-react-game/)

---

## Project Overview

Degen Wars brings turn-based artillery combat to the web. Its frontend is built with TypeScript and React, exposing the components used to handle match state, player information, and gameplay statistics.

Alongside the browser game, the repository examines Solana-based Web3 game infrastructure. The technical layout contains Rust programs built with Anchor, SPL Token integration, token metadata, and treasury accounts. Player accounts, digital collectibles, and a marketplace are listed as future development areas.

---

## Highlights

- Browser-based artillery matches with turn-by-turn gameplay
- Components for tracking and controlling game state
- Player statistics and other gameplay-related data
- Frontend implementation using TypeScript and React
- Anchor-organized Rust programs
- Solana connectivity with SPL Token support
- Token metadata and treasury account handling
- Planned support for player accounts, digital collectibles, and a marketplace

---

## Getting Started

Download the repository and enter its working directory:

```bash
git clone https://github.com/isaac-brooksvfz684/degen-wars-react-game.git
cd REPO
```

Install the dependencies specified by the project:

```bash
npm install
```

Launch the development server:

```bash
npm run dev
```

The terminal will display the local address to open in a compatible browser. If the repository includes dedicated Solana or Anchor scripts, run the appropriate project commands before exercising features that depend on blockchain connectivity.

---

## Playing and Testing

1. Open the hosted build, or run the application locally.
2. When requested, connect a compatible Solana wallet.
3. Start a turn-based artillery game.
4. Examine the available match-state and player-statistics data.
5. Try token functionality if the relevant Solana programs and accounts have been configured.
6. During local development, use browser developer tools and project logs to investigate application behavior.

Rust program work should follow the repository's Anchor process for building, testing, and deploying to the selected Solana environment.

---

## Environment Setup

Frontend behavior and Solana connections are controlled by the project's application and network configuration. If the repository includes an example environment file, copy it locally and provide values for the target network, program IDs, treasury accounts, and token metadata.

A local setup can use values in this form:

```env
VITE_SOLANA_NETWORK=devnet
VITE_RPC_URL=<solana-rpc-endpoint>
VITE_PROGRAM_ID=<anchor-program-id>
VITE_TREASURY_ACCOUNT=<treasury-account>
```

Only use variable names supported by the repository. Wallet, account, and deployment settings should correspond to the Solana environment under test.

---

## Prerequisites

- A current web browser
- Internet connectivity for hosted builds and Solana access
- Node.js and npm for running the frontend locally
- The TypeScript and React tooling included with the project
- Rust and Anchor when developing Solana programs
- A wallet compatible with Solana for wallet-enabled functionality
- Access to the chosen Solana network and its RPC endpoint
- Enough local disk space for dependencies and generated build files

---

## Common Questions

### Can I play Degen Wars in a browser?

Yes. The project is intended for browser use and delivers turn-based artillery gameplay through its web application.

### What role does Solana play?

Solana functionality in the project includes SPL Token integration, token metadata, treasury accounts, and Rust programs organized with Anchor.

### Is there a numbered release?

No numbered version is provided in the extracted project information. Check the hosted build and repository history to determine the current available state.

### What is the local update process?

Fetch the latest repository changes, refresh dependencies if package files were modified, and start the development server again:

```bash
git pull
npm install
npm run dev
```

### What should I check if blockchain functionality fails locally?

Confirm that the network and RPC endpoint are correct and that the program IDs, treasury accounts, token metadata, and connected wallet belong to the environment you are using. The required Anchor programs must also be built and deployed to that network.

### How do I submit a bug report?

Open an issue in the repository's GitHub issue tracker. Include your browser and operating environment, relevant configuration details, reproduction instructions, and any useful browser-console or program logs.

---

## Planned Work

The project profile names these future directions:

- Player account functionality
- Digital collectible support
- Marketplace features
- Further integration between the game systems and Solana

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
