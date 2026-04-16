# leadar

freelance marketplace scanner built with rust, python and rabbitmq.

monitors kwork, fl.ru and upwork — surfaces high-value orders using
z-score analysis, heatmaps and linear trends.

private access only.

## stack

| component     | tech                       |
| ------------- | -------------------------- |
| backend       | rust, axum, sqlx           |
| parsers       | python, httpx, faststream  |
| cache / dedup | dragonfly                  |
| broker        | rabbitmq                   |
| bot           | python, aiogram            |
| frontend      | svelte 5, typescript, vite |
| database      | postgresql                 |
| infra         | docker, nginx              |

## repos

| repo | description |
|---|---|
| [backend](../backend) | rest api, auth, analytics, z-score |
| [parser-kwork](../parser-kwork) | kwork.ru parser |
| [parser-fl](../parser-fl) | fl.ru parser |
| [parser-upwork](../parser-upwork) | upwork.com parser |
| [telegram-bot](../telegram-bot) | notifications and filters |
| [frontend](../frontend) | order feed, filters, charts |
| [infrastructure](../infrastructure) | docker, nginx, configs |
| [docs](../docs) | architecture and conventions |

---
> 🚧 work in progress — sprint 1
