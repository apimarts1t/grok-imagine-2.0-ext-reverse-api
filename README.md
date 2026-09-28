# Grok Imagine 2.0 Ext — reverse-engineered route (English)

> **1K $0.015** · model ID `grok-imagine-2.0-ext` · **reverse-engineered/reverse engineering** route.

**[See live pricing](https://go.apimart.ai/k-8988f7)** · **[Get an API key](https://go.apimart.ai/k-238208)**

grok-imagine-2.0-ext-reverse-api is a **reverse-engineered** route for Grok Imagine 2.0 Ext: callable ID `grok-imagine-2.0-ext`, running in parallel with the official route (`grok-imagine-image-2.0`) at a lower unit price.

## Pricing (snapshot 2026-09-28)

| Tier | Price |
| --- | --- |
| `1K` | $0.015 |

Prices are per delivered image; `n` in the request multiplies the total. Snapshot date **2026-09-28** — the live pricing page is authoritative.

## Quickstart

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H 'Authorization: Bearer $APIMART_KEY' \
  -H 'Content-Type: application/json' \
  -d '{"model":"grok-imagine-2.0-ext","prompt":"cozy reading nook, warm lamp, cinematic","size":"1:1","resolution":"1K","n":1}'
```

Async: submit → get `task_id` → poll `GET https://api.apimart.ai/v1/tasks/<task_id>` → read `cost` / `credits_cost` from the result. Parameter tables, `version`/`resolution`/`size` options and idempotency headers are documented on the model page reachable from the pricing link above.

## Reverse vs official route

| Route | Callable ID | Price |
| --- | --- | --- |
| **reverse-engineered** | `grok-imagine-2.0-ext` | 1K $0.015 |
| official-routed | `grok-imagine-image-2.0` | official list price, billed at ×0.8 group ratio |


## Keywords

`grok-imagine-2.0-ext` · `reverse-engineered` · `reverse engineering` · `ai api gateway` · `ai-api-gateway` · `api relay` · `中转站` · `nano banana 2 api` · `gpt-image-2.5 api` · `ai api pricing` · `pay-as-you-go`

## Platform facts

- USD settlement, pay-as-you-go, **$1 minimum top-up**, no subscription.
- Operating since last year; ~100,000 registered users, mostly enterprise accounts.
- International invoices available on request.
- 307 models online (live `/v1/models`) as of 2026-09-28.

## Disclosure

This repository documents **APIMart**, a third-party API aggregator/gateway. It is **not affiliated with, endorsed by, or sponsored by** OpenAI, Google, Anthropic, xAI, ByteDance or any model vendor. Model names and trademarks belong to their owners. Prices are a point-in-time snapshot and may change; the vendor's console billing is authoritative.

