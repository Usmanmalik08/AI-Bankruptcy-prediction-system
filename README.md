# Enterprise AI Bankruptcy Prediction Platform

This automated n8n workflow provides real-time financial risk assessments by combining custom mathematical logic with Generative AI analysis.

## 🚀 Key Features
- **Automated Data Ingestion:** Receives financial metrics via a secure Webhook API.
- **Advanced Risk Engine:** Custom JavaScript nodes calculate solvency, leverage, and liquidity ratios.
- **AI-Powered Insights:** Utilizes the **Groq Llama-3.1-8b** model to provide human-readable bankruptcy summaries and recovery recommendations.
- **Structured JSON Output:** Uses a **Structured Output Parser** to ensure error-free data delivery for enterprise integration.

## 🛠️ Installation & Setup
1. **Download the Workflow:** Download the `Enterprise AI Bankruptcy Prediction Platform.json` file from this repository.
2. **Import to n8n:** Open your n8n instance, click **Import from File**, and select the downloaded JSON.
3. **Configure Credentials:** Add your **Groq API Key** to the "Groq Chat Model" node.
4. **Deploy:** Set the Webhook to "Production" to start receiving real-time data.

## 👥 Group Responsibilities
- **Part 1 (Data Gateway):** [Name] — Webhook setup & Input Validation logic.
- **Part 2 (Math Engine):** [Name] — Financial Feature Engineering & ML Risk Scoring.
- **Part 3 (AI Brain):** [Name] — Groq LLM integration & Prompt Engineering.
- **Part 4 (Delivery):** [Name] — Structured Output Parsing & Final API Mapping.

## 📊 Sample Data Input
```json
{
  "assets": 1000000,
  "liabilities": 500000,
  "current_ratio": 2.0,
  "debt_to_equity": 0.5,
  "profit_margin": 0.2,
  "cashflow": 150000
}
