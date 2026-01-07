---
layout: "default"
title: "🚀 ace-tool - Simplify Codebase Searching Effortlessly"
description: "🛠️ Enhance code efficiency with ace-tool for seamless codebase indexing, semantic search, and AI prompt enhancement."
---
# 🚀 ace-tool - Simplify Codebase Searching Effortlessly

[![Download ace-tool](https://img.shields.io/badge/Download-ace--tool-brightgreen)](https://github.com/SantiagoRM9/ace-tool/releases)

---

## 📖 Overview

Welcome to ace-tool! This is a powerful tool designed to enhance your codebase management. With our tool, you can index your code seamlessly, perform semantic searches, and improve prompts for AI systems. 

---

## 💻 Download & Install

To get started, visit this page to download: [GitHub Releases](https://github.com/SantiagoRM9/ace-tool/releases).

### 🎯 System Requirements

- **Operating System:** Windows, macOS, or Linux
- **Node.js:** Version 14 or higher

### 📥 Installation Steps

1. **Open your terminal or command prompt.**
2. **Run the following command to install ace-tool globally:**

    ```bash
    npm install -g ace-tool@latest
    ```

3. **Alternatively, you can run it directly using npx:**

    ```bash
    npx -y ace-tool@latest --base-url <URL> --token <TOKEN>
    ```

---

## ⚙️ Configuration

### 🛠 MCP Settings

To set up ace-tool with your MCP server, add the following configuration to your MCP settings file. For example, in Claude Desktop's `claude_desktop_config.json`, include:

```json
{
  "mcpServers": {
    "ace-tool": {
      "command": "npx",
      "args": [
        "ace-tool",
        "--base-url", "YOUR_BASE_URL",
        "--token", "YOUR_TOKEN"
      ]
    }
  }
}
```

### 📋 Command Line Arguments

Here are the command line arguments you can use with ace-tool:

| Argument         | Required | Description                                      |
|------------------|----------|--------------------------------------------------|
| `--base-url`     | Yes      | API base URL for the indexing service            |
| `--token`        | Yes      | Authentication token for access                  |
| `--enable-log`   | No       | Enable logging to `.ace-tool/ace-tool.log`      |

---

## 🔍 Features

### 📜 Search Context

With ace-tool, you can search for relevant code based on a natural language query. Simply enter your query, and let the tool find the context for you. This makes it easier to discover where specific functions or variables are used in your code.

### 🛠 Additional Utilities

- **Indexing**: Quickly index your codebase for efficient searching.
- **Integration**: Works seamlessly with various other tools to enhance your workflow.
  
### 🔒 Security

Your authentication token ensures that your operations are secure. Always keep your token private and secure to prevent unauthorized access.

---

## 📞 Support

If you need help or have questions, check our [issue tracker](https://github.com/SantiagoRM9/ace-tool/issues) or contact the community on our forum.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/SantiagoRM9/ace-tool/blob/main/LICENSE) file for details.

---

Thank you for using ace-tool! We hope it makes your code management simpler and more efficient.