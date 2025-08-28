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
```

## 🤝 Contributing

We welcome contributions to this benchmark project! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details on how to submit pull requests, report issues, and contribute to the codebase.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔒 Security

If you discover a security vulnerability, please follow our [Security Policy](SECURITY.md) for responsible disclosure.

## 📝 Code of Conduct

This project adheres to the Contributor Covenant [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## 📞 Support

If you have questions or need help:
- Open an issue on GitHub
- Check our [Contributing Guidelines](CONTRIBUTING.md)
- Review our [Code of Conduct](CODE_OF_CONDUCT.md)
