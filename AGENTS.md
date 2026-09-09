# FareLens Agent Instructions

This repository is the FareLens prototype for Smart India Hackathon 2026.

## Allowed implementation stack

Use only:

- Python
- Scrapy
- Playwright
- Scrapfly
- PostgreSQL
- FastAPI
- Streamlit
- Plotly
- pandas
- NumPy
- SciPy
- regex / Python standard library

## Do not introduce

Do not add:

- Redis
- Caching layers
- Celery
- Queues
- Kafka
- Docker
- Kubernetes
- MongoDB
- Elasticsearch
- ORMs unless absolutely unavoidable
- Frontend frameworks
- Additional databases
- JavaScript application tooling

## Tooling notes

- uv is used for local Python dependency management.
- PowerShell 7 is the preferred local shell.
- Bun is not part of this project stack and should not be introduced.

## Project goal

Build a real-time Airfare Price Index, APIx, for India using automated scraping of airline and OTA portals, DGCA-weighted routes, fare decomposition, and Laspeyres index computation.
