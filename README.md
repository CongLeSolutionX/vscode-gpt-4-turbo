<!-- <h3 align="center"><img src="" height="64"><br>An Unofficial VS Code - GPT 4 Turbo extension</h3> -->

<p align="center">
    <a href="https://marketplace.visualstudio.com/items?itemName=gencay.vscode-chatgpt" alt="Marketplace version">
        <img src="https://img.shields.io/visual-studio-marketplace/v/gencay.vscode-chatgpt?color=orange&label=VS%20Code" />
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=gencay.vscode-chatgpt" alt="Marketplace download count">
        <img src="https://img.shields.io/visual-studio-marketplace/d/gencay.vscode-chatgpt?color=blueviolet&label=Downloads" />
    </a>
    <a href="https://github.com/gencay/vscode-chatgpt" alt="Github star count">
        <img src="https://img.shields.io/github/stars/gencay/vscode-chatgpt?color=blue&label=Github%20Stars" />
    </a>
</p>

## GPT 4 Turbo extension in VS Code open-sourced

This project is not ready to be on market place yet. If you use it, play with your own risks.

## Features

- ➕ Use GPT-4, GPT-3.5, GPT3 or Codex models using your OpenAI API Key
- 📃 Get streaming answers to your prompts in sidebar conversation window
- 🔥 Stop the responses to save your tokens.
- 📝 Create files or fix your code with one click or with keyboard shortcuts.
- ➡️ Export all your conversation history at once in Markdown format.
- Automatic partial code response detection. Continues and combines automatically, when response is cut off.
- Ad-hoc prompt prefixes for you to customize what you are asking ChatGPT
- Edit and resend a previous prompt
- Copy, insert or create new file from the code, ChatGPT is suggesting right into your editor.

## License

> If you are developing completely another extension and release it to the public, make sure you follow this.

This project is released under ISC License - See root License for details. Copyright notice and the respective permission notices must appear in all copies.

This repo is forked from the original repo here https://github.com/gencay/vscode-chatgpt.

## How to build and run

- Clone the repository to your local machine
- On the root directory, run `yarn` command to install the dependencies listed in `package.json`
- Within VS Code - run the project by simply hitting `F5`

## How to install locally

- Install `vsce` if you don't have it on your machine (The Visual Studio Code Extension Manager)
  - `npm install --global vsce`
- Run `vsce package`
- Follow the <a href="https://code.visualstudio.com/docs/editor/extension-marketplace#_install-from-a-vsix">instructions</a> and install manually.
