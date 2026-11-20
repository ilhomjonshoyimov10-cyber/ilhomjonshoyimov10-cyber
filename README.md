# Ilhomjon Shoyimov

**AI and Python developer.** I build LLM applications (agents, RAG, chatbots) and deep learning models,
and ship them as working products with tests, Docker, CI and live demos.

🇺🇿 AI va Python dasturchisi: LLM ilovalari (agentlar, RAG, chatbotlar) va deep learning modellarini yarataman
hamda ularni test, Docker va CI bilan ishlaydigan mahsulotga aylantiraman.

📫 ilhomjonshoyimov10@gmail.com

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| **[ATLAS](https://github.com/ilhomjonshoyimov10-cyber/atlas)** · [live](https://atlas-bozor.vercel.app) | Deep learning forecasts of price ranges for 37 markets from prices, seasonality and news. Transformer + cross-asset attention + FinBERT news branch, conformal calibration, leakage-safe walk-forward evaluation, automated retraining. | PyTorch, FinBERT, FastAPI, React, GitHub Actions, Vercel |
| **[PDF RAG Assistant](https://github.com/ilhomjonshoyimov10-cyber/pdf-rag-assistant)** | Ask questions about PDFs, get answers with page citations. Hybrid BM25 + vector retrieval with RRF, Uzbek-aware search, measured on an evaluation set (hit@1 0.68 → 0.86 from stemming). | Python, FastAPI, NumPy, OpenAI-compatible LLMs |
| **[Tool-Calling Agent](https://github.com/ilhomjonshoyimov10-cyber/tool-calling-agent)** | AI agent written from scratch: picks and runs tools (Central Bank of Uzbekistan rates, weather, Wikipedia, calculator, to-do list), handles tool errors, shows every step in a web UI. | Python, FastAPI, Pydantic, function calling |
| **[Telegram AI Assistant](https://github.com/ilhomjonshoyimov10-cyber/telegram-ai-assistant)** | Telegram bot with conversation memory in PostgreSQL, daily limits per user, token accounting and admin stats. | aiogram 3, SQLAlchemy async, PostgreSQL, Docker |
| **[Sanat Hoca Türkçe](https://github.com/ilhomjonshoyimov10-cyber/sanat-hoca-turkce)** · [live](https://sanat-hoca-turkce.vercel.app) | Learning platform for a Turkish language centre: courses, 12 practice games, groups, teacher panel, AI tutor with switchable providers, 2FA. | Next.js, NestJS, PostgreSQL, Prisma, Redis, Docker |
| **[Muzey](https://github.com/ilhomjonshoyimov10-cyber/muzey-)** | Telegram Mini App that turns photos and videos into a walkable 3D museum, shared by link or QR code. | Vercel functions, Supabase, three.js |
| **Aeroport** ([backend](https://github.com/ilhomjonshoyimov10-cyber/aeroport-backend), [frontend](https://github.com/ilhomjonshoyimov10-cyber/aeroport-frontend)) | Airport services system: flights, tickets, baggage, terminal services, statistics. | Django REST, JWT, React, Chart.js |

## Tech

**AI / ML:** PyTorch · Transformers · LLM APIs (Gemini, OpenAI-compatible) · RAG · agents and function calling · evaluation  
**Backend:** Python · FastAPI · Django REST · aiogram · SQLAlchemy · PostgreSQL · Redis · Node.js · NestJS  
**Frontend:** React · Next.js · TypeScript · three.js  
**Delivery:** Docker · GitHub Actions · Vercel · pytest

## How I work

- Tests come with the code, including the failure paths (provider down, bad input, limits).
- I measure before I claim: evaluation sets, ablations and honest "not significant" results.
- Every project runs with one command (`docker compose up`) and documents its limitations.
