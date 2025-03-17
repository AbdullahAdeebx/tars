# Tars - Your Terminal AI Companion

[![Created by Abdullah Adeeb](https://img.shields.io/badge/Created%20by-Abdullah%20Adeeb-blue)](https://www.abdullahadeeb.xyz)


Tars is a command-line interface (CLI) application that lets you chat with Google's Gemini AI directly from your terminal. It uses Google's Gemini API via an OpenAI-compatible interface.

## Features

- **Interactive Chat Mode**: Have a back-and-forth conversation with the AI
- **Single Query Mode**: Get quick answers without entering a chat session
- **Secure API Key Storage**: Your Google API key is stored securely in your home directory

## Installation

```bash
# Install globally from npm
npm install -g @abdullahadeeb/tars
```

## Usage

### Interactive Chat Mode

Start an interactive chat session with the AI:

```bash
tars
```

This will start a conversation where you can type messages and receive responses from the AI. Type `exit`, `quit`, or `bye` to end the session.

### Single Query Mode

Get a quick answer without starting a chat session:

```bash
tars "What is the capital of France?"
```

## First-Time Setup

On your first run, Tars will prompt you to enter your Google API key. This key will be saved in your home directory (`~/.tars_api_key`) for future use.

To get a Google API key:
1. Go to the [Google AI Studio](https://aistudio.google.com/)
2. Create an account or sign in
3. Navigate to the API section and create a new API key

## Troubleshooting

### API Key Issues

If you need to update your API key, you can delete the existing key file and run Tars again:

- On Windows: Delete `%USERPROFILE%\.tars_api_key`
- On macOS/Linux: Delete `~/.tars_api_key`


## For Developers

### Local Development Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/AbdullahAdeebx/tars
   cd tars
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Link the package locally to test it:
   ```bash
   npm link
   ```

4. Now you can run the CLI tool:
   ```bash
   tars
   ```

## Requirements

- Node.js 14.0 or higher

## License

MIT 