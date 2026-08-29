# AI Stock Recommendation Agent

An AI-powered stock recommendation agent built using n8n.

## 🚀 Overview

This project uses an AI agent to analyze a user's existing stock
portfolio and suggest a stock that could potentially improve
portfolio diversification.

## 🔄 Workflow

User
↓
n8n Chat Trigger
↓
AI Agent
↓
Google Sheets → Portfolio Data
↓
Marketstack → Market Data
↓
Google Gemini → Analysis
↓
Stock Recommendation

## 🛠️ Tech Stack

- n8n
- Google Gemini
- Marketstack API
- Google Sheets
- AI Agent / Tool Calling

## ✨ Features

- Chat-based interaction
- Reads existing portfolio data
- Retrieves market data through an API
- Uses an AI agent for analysis
- Considers existing holdings and sector exposure
- Provides reasoning and potential risks
- Uses tool calling to interact with external services

## 📁 Files

- `stock-recommendation-agent.json` – Exported n8n workflow

## ⚙️ Setup

1. Import the JSON workflow into n8n.
2. Configure Google Gemini credentials.
3. Configure Marketstack API credentials.
4. Connect the Google Sheets account.
5. Select the portfolio spreadsheet and sheet.
6. Activate the workflow.

## ⚠️ Disclaimer

This project is for educational purposes only and does not provide
guaranteed financial advice or investment recommendations.

API keys and credentials are not included in this repository.
