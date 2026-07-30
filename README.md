# GPUsMarket Desktop

The macOS app for hosting your Mac on [GPUsMarket](https://gpusmarket.com) — earn by serving AI models from your Apple Silicon machine. No terminal needed:

1. **[Download GPUsMarket for Mac](https://github.com/jyswee/gpusmarket-desktop/releases/latest/download/GPUsMarket-arm64.dmg)** (Apple Silicon)
2. Open the dmg, drag **GPUsMarket** to Applications
3. Sign in with your gpusmarket.com account
4. The onboarding wizard detects your Mac, sets your price, checks [Ollama](https://ollama.com/download/mac), and connects — you're live on the marketplace

## Features

- One-click host onboarding wizard (chip/memory auto-detected)
- Live hosting status + marketplace online/offline toggle
- Ollama model manager — list, pull, and publish models to your listing
- Earnings dashboard (monthly net, mesh pot, Stripe payouts)
- Start at login
- Renter portal built in

## Requirements

- Apple Silicon Mac (M1 or later), macOS 12+
- [Ollama](https://ollama.com/download/mac) (the wizard walks you through it)
- A [gpusmarket.com](https://gpusmarket.com) account

> **Note (current build):** the app is not yet notarized. On first launch, right-click **GPUsMarket.app → Open → Open**. A notarized build is coming and will replace the download at the same URL.

Prefer the terminal? `npx easytyga --key gph_...` does the same tunnel — see [easytyga](https://github.com/jyswee/easytyga).
