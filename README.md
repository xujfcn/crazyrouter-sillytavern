# 🎭 SillyTavern + Crazyrouter Setup Guide

> Use Claude, GPT, Gemini and 300+ models in SillyTavern — Save 45% on API costs.

[Crazyrouter](https://crazyrouter.com?ref=github) — One API key for all AI models.

## 💰 Price Comparison

| Model | Official Price | Crazyrouter | Savings |
|-------|---------------|-------------|---------|
| Claude Opus 4 | $15 / $75 | $8.25 / $41.25 | **45%** |
| Claude Sonnet 4 | $3 / $15 | $1.65 / $8.25 | **45%** |
| GPT-4o | $2.50 / $10 | $1.38 / $5.50 | **45%** |

## ⚡ Setup Steps

### 1. Get Crazyrouter API Key
Sign up at [crazyrouter.com](https://crazyrouter.com?ref=github)

### 2. Configure in SillyTavern

#### Option A: OpenAI-Compatible Mode
1. Click the **API Connection** icon (plug icon)
2. Select **Chat Completion (OpenAI)**
3. Set **Custom Endpoint**: `https://crazyrouter.com/v1`
4. Set **API Key**: `sk-your-crazyrouter-key`
5. Click **Connect**

#### Option B: Claude Native Mode
1. Select **Claude** as API type
2. Set **Custom Endpoint**: `https://crazyrouter.com`
3. Set **API Key**: `sk-your-crazyrouter-key`
4. Select Claude model

### 3. Select Model
Choose from: `claude-sonnet-4-20250514`, `claude-opus-4-20250514`, `gpt-4o`, etc.

## 🎯 Recommended Models for RP

| Use Case | Model | Why |
|----------|-------|-----|
| Best quality RP | Claude Opus 4 | Most creative & coherent |
| Daily RP (value) | Claude Sonnet 4 | Great quality, affordable |
| Fast responses | GPT-4o | Quick turnaround |
| Long context | Gemini 2.5 Pro | 1M token window |

## ⚙️ Recommended Settings

| Parameter | Value | Notes |
|-----------|-------|-------|
| Temperature | 0.8-1.0 | Higher = more creative |
| Top P | 0.95 | Good diversity |
| Max Tokens | 1000-2000 | Response length |
| Frequency Penalty | 0.3 | Reduce repetition |

## ❓ FAQ

**Q: "Failed to connect" error?**
A: Check Base URL includes `/v1` for OpenAI mode. For Claude mode, no `/v1`.

**Q: Model list is empty?**
A: Type model name manually, e.g. `claude-sonnet-4-20250514`.

**Q: Responses cut off?**
A: Increase Max Tokens to 2000-4000.

## 🔗 Links
- 🌐 [Crazyrouter](https://crazyrouter.com?ref=github) | 🎭 [SillyTavern](https://github.com/SillyTavern/SillyTavern) | 💬 [Telegram](https://t.me/crzrouter)

## 📄 License
MIT
