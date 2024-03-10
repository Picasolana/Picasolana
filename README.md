# Picassolana: Pay-to-Earn Contest Game

## Introduction

Picassolana is an innovative Pay-to-Earn prompt-engineering game where creativity meets the blockchain. Each day, we publish an image, and contestants across the web and Telegram can compete by attempting to find a prompt that leads the closest to the published image. Contestants are scored from 0 to 100, and the best submission of the day wins an NFT generated exclusively for the occasion. With a leaderboard to track top performers and a shareable option to spread the word, Picassolana is not just a game – it's a daily NFT challenge for the best at prompt engineering.

- [Demo Live App](picassolano-client.vercel.app)
- [Demo Telegram](https://t.me/picassolana_bot)
- [Demo Video](https://www.loom.com/share/c4e2463149334fc088704143eff7028e?sid=cce481cd-ccec-495a-95e6-2fb768d88d53)
- [Pitch Deck](https://www.canva.com/design/DAF_CIhoANg/tHxmZ3rtWPjCzl5oArnL5g/edit?utm_content=DAF_CIhoANg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Documentation](#documentation)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

## Installation

The Picassolana ecosystem comprises several components, including a web app, backend services, a Coophive module for cooperative interactions, a Telegram bot, and an NFT smart contract. To set up the Picassolana project, follow the installation steps for each repository:

1. **Web App (`picassolana-client`)**: The front-facing web application for users to interact with the contest.
   - Clone the repository and follow the README within for web app setup instructions.
   - https://github.com/Picasolana/picassolano-client
2. **Backend Services (`backend`)**: Backend infrastructure handling game logic, scoring, and data management.
   - Clone and set up according to the provided setup instructions in its README.
   - https://github.com/Picasolana/backend
3. **Coophive Module (`sdxl-lightning-coophive-module`)**: Manages cooperative interactions and functionalities.
   - Utilize Docker to deploy the Coophive module as described in its README.
   - https://github.com/Picasolana/sdxl-lightning-coophive-module
4. **Telegram Bot (`telegram_new`)**: Allows users to participate in the contest via Telegram.
   - Instructions for setting up the Telegram bot are available within the repository.
   - https://github.com/Picasolana/telegram_new
5. **NFT Smart Contract (`NFT`)**: Manages the creation and awarding of NFTs to contest winners.
   - Follow the smart contract deployment instructions detailed in the repository.
   - https://github.com/Picasolana/NFT

## Usage

To participate in the Picassolana contest, users can either visit the web app or interact with the Telegram bot @picassolana_bot. Each day, a new challenge is posted, and users can submit their prompts in an attempt to match the published image as closely as possible.

## Features

- Daily image contests with a Pay-to-Earn model.
- Real-time leaderboard tracking contestant scores.
- NFT rewards for daily contest winners.
- Cross-platform participation through the web and Telegram.
- Shareable links to promote the game across social networks.

## Dependencies

Picassolana's components rely on various dependencies, including but not limited to:

- Node.js and TypeScript for backend and bot development.
- Docker for deploying the Coophive module.
- Specific library and framework dependencies are listed in the respective repositories.

## Configuration

Configuration details for each component of the Picassolana project are provided within the individual repositories. These include environment variables, API keys, and other necessary configurations for the web app, backend, Coophive module, Telegram bot, and NFT smart contract.

## License

The Picassolana project is licensed under the MIT License. See the `LICENSE` file in each repository for more details.
