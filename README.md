# AsynchronousAgent_Jules

This repository is part of a benchmark project comparing autonomous coding agents
(Jules, Devin, Genspark, and Abacus) across two phases:

1. **Messy Repo Challenge** – intentionally seeded with outdated dependencies, failing/flaky tests, and missing validation.
2. **Prediction App Build** – a full-stack app with FastAPI, SQLite, Next.js, and Brier scoring.

## Getting Started
```bash
# Install Node dependencies
npm install

# Run JS/TS tests
npm -w apps/web test
npm -w libs/shared test

# Python dependencies
cd services/api
pip install -r requirements.txt
pytest
