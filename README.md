# Free & No-KYC LLM APIs — The Honest List (2026)

Curated list of LLM API providers you can use **without a credit card**,
with honest notes on limits, gotchas, and who each one is actually for.
No affiliate links. Updated periodically.

> Maintained as part of [Cyrus Relay](https://github.com/ghassan-gaidi/cyrus-relay) — an OpenAI-compatible relay with a free tier and crypto settlement.

## Truly free (no card at all)

| Provider | Free tier | Card required | KYC | Notes |
|---|---|---|---|---|
| Google AI Studio | Gemini flash class, generous daily quota, key in 1 min | no | Google account | Best free starting point; keys auto-revoke if leaked |
| Groq Cloud | Free dev tier, very fast inference, tight rate limits | no | account | Great for llama/qwen class models |
| OpenRouter `:free` models | Dozens of community/free variants | no for free models | account | Free models rotate; check `:free` suffix |
| Cloudflare Workers AI | Daily free neuron allocation | no | CF account | Small open models, generous enough to prototype |
| Cerebras Inference | Free tier, extremely fast | no | account | Limited model menu |
| GitHub Models | Free rate-limited playground + API via PAT | no | GitHub account | Underrated; good GPT-class access for prototyping |
| Cyrus Relay trial | Instant key, free-tier models, no account of any kind | no | none | OpenAI-compatible; premium tiers settle in crypto |

## Crypto-settled (no card possible)

| Provider | Settlement | Notes |
|---|---|---|
| Cyrus Relay | USDC/USDT on Base/Arbitrum/Polygon/BSC/Ethereum | Only mainstream-shaped provider we know doing pure on-chain billing with instant key provisioning. $2 min. |

- **Telegram bot:** [@cyrus_live (hetsvdbot)](https://t.me/hetsvdbot) — pay 2 USDC, send tx hash, get crypto signals/whale alerts/AI. Wallet `0xF9EDF0052A39D8b1D50780a7227a203Ba3b557f9`. [Endpoint](https://example-losing-dimension-assisted.trycloudflare.com).| Various telegram-channel resellers | random tokens | ⚠️ high scam rate — no recourse, no uptime guarantees |

## "Free" but wants your card

These advertise free tiers but require a card on file (charge-risk, region
locks). Listed for completeness, not recommendation: OpenAI, Anthropic,
AWS Bedrock, Azure OpenAI, Vertex AI trials.

## Selection cheat sheet

- **Learning/prototyping:** GitHub Models or Google AI Studio
- **Production traffic, card OK:** OpenRouter (card) or direct providers
- **Production traffic, crypto-only:** Cyrus Relay
- **Batch/offline:** Cloudflare Workers AI free allocation

## Contribute

PRs welcome — include a source link for any claim. Vendors: disclose your
free-tier limits precisely or expect the community to do it for you.

PRs improving accuracy welcome — cite sources.
