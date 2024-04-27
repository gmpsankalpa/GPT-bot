# Discord Chatbot using OpenAI

This Discord bot utilizes OpenAI's GPT-3.5 model to create conversational responses in a designated channel.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Commands](#commands)
- [Acknowledgements](#acknowledgements)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the Discord Chatbot powered by OpenAI! This bot leverages the advanced capabilities of OpenAI's GPT-3.5 model to create engaging and natural conversation within your Discord server. Whether you're looking to entertain users, provide assistance, or simply engage in casual conversation, this bot is designed to enhance the interactive experience in your Discord community.

With its ability to generate responses based on context and previous messages, the bot creates a seamless conversational flow, making interactions feel more human-like and immersive. By integrating state-of-the-art AI technology, this bot opens up a world of possibilities for enriching communication and engagement within your Discord channels.

## Prerequisites

Before running the bot, ensure you have the following installed:

- Node.js
- npm (Node Package Manager)

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/gmpsankalpa/GPT-bot.git

2. Navigate to the project directory:
    ```bash
    cd discord-openai-bot

3. Install dependencies:
    ```bash
    npm install

## Configuration

1. Rename `.env.example to .env`:
    ```bash
    mv .env.example .env

2. Open the `.env` file and fill in the following values:
- `API_KEY`: Your OpenAI API key
- `CHANNEL_ID`: The ID of the Discord channel where the bot will operate
- `TOKEN`: Your Discord bot token

## Usage

- To start the bot, run:
    ```bash
    npm start

- The bot will now be online and ready to respond to messages in the designated channel.

## Commands

The bot doesn't respond to commands prefixed with !.

## Acknowledgements

- `Discord.js` - Discord API wrapper
- `OpenAI` - AI language model provider

## Contributing

Contributions to this project are welcome. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Create a new Pull Request.

## License

This project is licensed under the [MIT](LICENSE) License.

---

<p align="center">
<b>
  Repo Details 🤙
</b>
</p>

<div align="center">

   ![repo size](https://img.shields.io/github/repo-size/gmpsankalpa/GPT-bot?label=Repo%20Size&style=for-the-badge&labelColor=black&color=20bf6b)
   ![GitHub forks](https://img.shields.io/github/forks/gmpsankalpa/GPT-bot?&labelColor=black&color=0fb9b1&style=for-the-badge)
   ![GitHub stars](https://img.shields.io/github/stars/gmpsankalpa/GPT-bot?&labelColor=black&color=f7b731&style=for-the-badge)
   ![GitHub LastCommit](https://img.shields.io/github/last-commit/gmpsankalpa/GPT-bot?logo=github&labelColor=black&color=d1d8e0&style=for-the-badge)

</div>

<p align="center">
<b>
  Deploy status badge 🤖
</b>
</p>  

<div align="center">
   
   [![Netlify Status](https://api.netlify.com/api/v1/badges/f8c54f31-10f6-42a4-80e6-342090a3c60e/deploy-status)](https://app.netlify.com/sites/gmp-GPT-bot/deploys)
</div>