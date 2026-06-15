<div align="center">

# Buzz Desktop Transcription

Buzz transcribes and translates audio offline on your personal computer. It is powered by OpenAI's Whisper.

</div>

## 🎙️ Overview

Buzz is an offline audio transcription and translation project designed for use on a personal computer. Its core purpose is to help convert spoken audio into text and translate audio content without relying on cloud-based processing. The project is powered by OpenAI's Whisper, a speech recognition system used for transcription and translation workflows.

This repository also includes a website built with [Docusaurus 2](https://docusaurus.io/), a modern static website generator. The website can be run locally for development and built into static content for hosting.

## ✨ Key Points

- Transcribes audio on a personal computer
- Translates audio content
- Works offline
- Powered by OpenAI's Whisper
- Includes a Docusaurus 2 website
- Uses Yarn for website development commands

## 🧰 Technology

| Purpose | Technology |
|---|---|
| Website generator | Docusaurus 2 |
| Package manager / scripts | Yarn |
| Speech transcription and translation engine | OpenAI Whisper |

## 🛠️ Website Development

Install website dependencies:

```bash
yarn
```

Run the local development server:

```bash
yarn start
```

This starts a local development server and opens a browser window. Most website changes are reflected live without needing to restart the server.

Build the static website:

```bash
yarn build
```

The build command generates static content in the `build` directory, which can be served by any static content hosting service.

## 🚀 Deployment

Deploy using SSH:

```bash
USE_SSH=true yarn deploy
```

Deploy without SSH:

```bash
GIT_USER=<Your GitHub username> yarn deploy
```

When using GitHub Pages for hosting, this command can build the website and push the result to the `gh-pages` branch.

## 📌 Use Cases

Buzz is relevant for workflows where audio needs to be converted into readable text or translated while keeping processing local to a personal computer. Typical use cases include:

- Creating transcripts from recorded conversations
- Translating spoken audio
- Working with audio content without cloud transcription services
- Preparing text from speech for notes, documentation, or review
- Supporting offline transcription workflows

## ❓ FAQ

### Does Buzz work offline?

Yes. The project description states that Buzz transcribes and translates audio offline on a personal computer.

### What powers Buzz transcription and translation?

Buzz is powered by OpenAI's Whisper.

### Is this repository related to a website?

Yes. The included README content describes a website built with Docusaurus 2.

### How is the website run locally?

The documented local development command is:

```bash
yarn start
```

### How is the website built?

The documented build command is:

```bash
yarn build
```

## 🔎 Keywords

Buzz, offline transcription, audio transcription, audio translation, Whisper transcription, OpenAI Whisper, speech to text, offline audio processing, Docusaurus website.
