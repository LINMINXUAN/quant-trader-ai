# Crypto Quant AI Bot

An AI-powered automated crypto trading platform with:

- 🤖 AI Strategy generation using ChatGPT & Codex
- 📊 Real-time dashboard for positions, PnL, and metrics
- 💰 Strict capital & risk management
- 🔁 Automated execution via exchange APIs (Binance, OKX, etc.)

## 🛠 Stack

- Frontend: Next.js + Tailwind
- Backend: FastAPI / Flask
- Strategy Engine: Python + ccxt
- AI Agent: OpenAI GPT-4 + LangChain + Codex
- Database: PostgreSQL + Redis
- Deployment: Docker + GCP/AWS

## 🚀 Quick Start

```bash
# clone repo
git clone https://github.com/yourname/crypto-quant-ai-bot.git
cd crypto-quant-ai-bot

# setup backend
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

# setup frontend
cd ../frontend
npm install
npm run dev
