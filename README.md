# inSEIght Bot - SEI Blockchain Portfolio Tracker

[![Status](https://img.shields.io/badge/status-live-brightgreen.svg)]() [![Telegram](https://img.shields.io/badge/Telegram-inSEIghtBot-blue.svg)](https://t.me/inSEIghtBot) ![Hackathon](https://img.shields.io/badge/Hackathon-Project-orange.svg)

**Get intelligent insights into your crypto portfolio through a smart Telegram bot that analyzes SEI blockchain data.**

## 🚀 Quick Start

Try the bot now on Telegram: **[@inSEIghtBot](https://t.me/inSEIghtBot)**

Simply send a wallet address, Space.ID name, or ENS name to get instant portfolio insights and analysis.

## ✨ Features

- 💰 **Portfolio Value Tracking** - Real-time portfolio valuation
- 📊 **Detailed Analytics** - Performance metrics and profit/loss analysis  
- 🎨 **NFT Integration** - Track your NFT holdings and values
- 📈 **Price Alerts** - Get notified of significant changes
- 🔍 **Deep Insights** - AI-powered analysis of your holdings
- 🌐 **Multi-Format Support** - Works with wallet addresses, Space.ID, and ENS names

## 🏗️ Architecture

This hackathon project is built using:

- **[n8n](https://n8n.io/)** - Workflow automation platform
- **[FlowMCP](https://github.com/FlowMCP)** - Model Context Protocol server framework
- **[MCP Server](https://community.flowmcp.org/inseight)** - Custom SEI blockchain data provider
- **Telegram Bot API** - User interface and interaction
- **SEI Blockchain** - Primary data source

### System Flow

1. User sends query to Telegram bot
2. n8n workflow processes the request
3. FlowMCP server fetches SEI blockchain data
4. AI analyzes and formats the response
5. Bot returns intelligent insights to user

## 🌐 Live Demo

Visit our project website: [inSEIght Bot Demo](https://a6b8.github.io/inSEIght/)

## 🛠️ Technical Implementation

### MCP Server Integration

The bot leverages a custom MCP server deployed at `https://community.flowmcp.org/inseight` that provides:

- Real-time SEI blockchain data
- Portfolio aggregation
- Asset valuation
- Historical performance metrics

### FlowMCP Framework

Built using the FlowMCP ecosystem (https://www.flowmcp.org) which enables:
- Standardized blockchain data access
- Scalable workflow automation
- Extensible plugin architecture

## 🤖 Bot Commands

- Send any **wallet address** to get portfolio overview
- Use **Space.ID names** (e.g., `alice.sei`) for easy lookup
- Send **ENS names** for cross-chain analysis
- Ask questions about your portfolio in natural language

## 🎯 Hackathon Goals

This project demonstrates:
- ✅ Integration with SEI blockchain
- ✅ Real-time data processing
- ✅ User-friendly Telegram interface
- ✅ AI-powered portfolio analysis
- ✅ Multi-name resolution (Space.ID, ENS)
- ✅ Production-ready deployment

## 📱 Screenshots

The website includes an interactive demo showing the bot in action with sample portfolio data and real-time chat simulation.

## 🔗 Links

- **Bot**: [@inSEIghtBot](https://t.me/inSEIghtBot)
- **Website**: https://a6b8.github.io/inSEIght/
- **FlowMCP**: https://www.flowmcp.org
- **MCP Server**: https://community.flowmcp.org/inseight
- **SEI Network**: https://sei.network

## 🏆 Hackathon Team

Built for the SEI Hackathon - showcasing the power of intelligent blockchain data analysis through conversational AI.

---

*© 2025 inSEIght Bot - Smart Crypto Portfolio Insights*