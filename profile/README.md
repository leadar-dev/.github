# leadar

freelance marketplace scanner built with rust, python and rabbitmq.

monitors kwork, fl.ru and upwork — surfaces high-value orders using 
z-score analysis, heatmaps and linear trends.

## stack

| component | tech |
|---|---|
| backend | rust, axum, sqlx |
| parsers | python, httpx, faststream |
| broker | rabbitmq |
| bot | python, aiogram |
| frontend | vanilla js |
| database | postgresql |

## repos

| repo | description |
|---|---|
| [backend](../backend) | rest api, auth, analytics |
| [parser-kwork](../parser-kwork) | kwork parser |
| [parser-fl](../parser-fl) | fl.ru parser |
| [parser-upwork](../parser-upwork) | upwork parser |
| [telegram-bot](../telegram-bot) | notifications and analytics |
| [frontend](../frontend) | order feed and filters |
| [infrastructure](../infrastructure) | docker, nginx, configs |

---
> 🚧 work in progress — sprint 1
