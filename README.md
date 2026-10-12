# 🎭 SillyTavern + Crazyrouter Setup Guide

> Use Claude, GPT, Gemini and available models in SillyTavern .

[Crazyrouter](https://crazyrouter.com?utm_source=github&utm_medium=github&utm_campaign=dev_community) — One API key for compatible models.

## Current prices

[Current model prices](https://crazyrouter.com/en/pricing). Rates depend on the model, account group and billing unit; there is no universal discount. Check input, output, cache and task charges before use.

## ⚡ Setup Steps

### 1. Get Crazyrouter API Key
Sign up at [crazyrouter.com](https://crazyrouter.com?utm_source=github&utm_medium=github&utm_campaign=dev_community)

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
Choose from: `claude-sonnet-4-6`, `claude-opus-4-8`, `gpt-4o`, etc.

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
A: Type model name manually, e.g. `claude-sonnet-4-6`.

**Q: Responses cut off?**
A: Increase Max Tokens to 2000-4000.

## 🔗 Links
- 🌐 [Crazyrouter](https://crazyrouter.com?utm_source=github&utm_medium=github&utm_campaign=dev_community) | 🎭 [SillyTavern](https://github.com/SillyTavern/SillyTavern) | 💬 [Telegram](https://t.me/crzrouter)

## 📄 License
MIT
