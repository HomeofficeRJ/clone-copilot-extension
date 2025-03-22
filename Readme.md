# Clone Copilot - Mistral AI Powered Code Completion

Clone Copilot is a VS Code extension that provides AI-powered code completions using Mistral AI's language models. It's designed to be a free alternative to GitHub Copilot, offering inline code suggestions as you type.

[![VS Code Marketplace](https://img.shields.io/visual-studio-marketplace/v/serianonim.clone-copilot.svg?label=VS%20Code%20Marketplace&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=serianonim.clone-copilot)
[![Open VSX Registry](https://img.shields.io/open-vsx/v/serianonim/clone-copilot?label=Open%20VSX%20Registry&style=flat-square)](https://open-vsx.org/extension/serianonim/clone-copilot)

![Clone Copilot Demo](images/demo.gif)

## 🌟 Features

- **Inline Code Completions**: Get real-time code suggestions as you type
- **Multiple Model Support**: Choose from different Mistral AI models including:
  - `mistral-small-latest`: Balanced performance and speed
  - `mistral-medium-latest`: More powerful completions
  - `mistral-large-latest`: Most powerful model for complex code
  - `codestral-latest`: Specialized for code completion with Fill-in-the-Middle capability
- **Fill-in-the-Middle (FIM)**: When using `codestral-latest`, the extension can understand code context both before and after your cursor
- **Easy Toggle**: Enable or disable completions with a single click in the status bar
- **Customizable**: Configure the model and other settings through VS Code preferences

## 🚀 Installation

### From VS Code Marketplace

1. Install the extension from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=serianonim.clone-copilot)
2. Get a Mistral AI API key from [https://console.mistral.ai/](https://console.mistral.ai/)
3. Set up your API key using one of these methods:
   - **Environment Variable (Recommended)**: Create an environment variable named `MISTRAL_API_KEY` with your API key
   - **VS Code Settings**: Enter your API key when prompted after enabling the extension

### From Open VSX Registry

For VSCodium or other open-source VS Code alternatives:

1. Install the extension from the [Open VSX Registry](https://open-vsx.org/extension/serianonim/clone-copilot)
2. Follow the same API key setup steps as above

### Manual Installation

You can also download the latest `.vsix` file from the [releases](https://github.com/gabaci72/clone-copilot-extension/releases) section and install it manually:

```bash
code --install-extension clone-copilot-x.x.x.vsix
```

## 🔧 Usage

1. After installation, click the "Clone Copilot" icon in the status bar to enable completions
2. Start typing code and see inline suggestions appear
3. Press Tab to accept a suggestion, or continue typing to ignore it

## ⚙️ Configuration

This extension contributes the following settings:

* `cloneCopilot.enabled`: Enable/disable inline completions
* `cloneCopilot.mistralApiKey`: Your Mistral AI API key
* `cloneCopilot.model`: The Mistral AI model to use for completions

## 🔒 Privacy

Your code is sent to Mistral AI's API for processing. Please review Mistral AI's privacy policy for details on how your data is handled.

## 📝 License

Proprietary. All rights reserved.

This software is protected by copyright law. Unauthorized reproduction or distribution of this software, or any portion of it, may result in severe civil and criminal penalties, and will be prosecuted to the maximum extent possible under law.

## 🙏 Credits

This extension uses the Mistral AI API to provide code completions.

## 📣 Feedback

Feedback is welcome! Please open an issue on this repository or contact us through email for any questions or suggestions.

## ⚠️ Disclaimer

This extension is not affiliated with GitHub Copilot or Mistral AI. It is an independent project that uses Mistral AI's API services.

## 🔮 Future Plans

- **More Language Support**: Enhance support for additional programming languages
- **Local Model Support**: Add options for running models locally for privacy
- **Improved Context Understanding**: Better project structure awareness
- **User Preferences**: Customize to your coding style
- **Test Generation**: Generate test cases for your code

---

*Note: This repository contains only the release builds and documentation for Clone Copilot. For more information about the extension, please visit the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=serianonim.clone-copilot) or [Open VSX Registry](https://open-vsx.org/extension/serianonim/clone-copilot).*