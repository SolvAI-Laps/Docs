# Environment Requirements for SolvAI

This document outlines the necessary environment setup and requirements for running the SolvAI platform. Follow the guidelines below to ensure smooth deployment and operation of SolvAI's AI-driven services.

---

## 1. Operating System
- **Recommended:** Linux-based distributions (Ubuntu 20.04 or newer)
- **Supported:** macOS, Windows 10 or higher

---

## 2. Programming Languages
- **Python:** Version 3.9 or above

---

## 3. Frameworks and Libraries
The following Python libraries are required:
- `openai`
- `web3`
- `requests`
- `flask`
- `fastapi`
- `pandas`
- `numpy`
- `python-decouple`
- `gunicorn`

You can install these dependencies using:
```bash
pip install -r requirements.txt
```

---

## 4. APIs Utilized
Ensure the following API services are properly configured:

### 4.1 OpenAI API
- API key required
- Use for AI agent communication and NLP tasks

### 4.2 Coinbase API
- API key and secret required
- Use for fetching cryptocurrency price data and financial insights

### 4.3 CoinGecko API
- Free tier supported
- Use for retrieving market trends, ICOs, and token information

### 4.4 Ethereum API
- Infura or Alchemy API key required
- Use for blockchain interactions and on-chain data analysis

---

## 5. Hardware Requirements
- **Processor:** Quad-core CPU or better
- **Memory:** 8GB RAM minimum, 16GB recommended
- **Storage:** At least 50GB of free space

---

## 6. Networking
- **Internet Speed:** Minimum 10 Mbps
- **Ports:** Ensure the following ports are open:
  - `80` (HTTP)
  - `443` (HTTPS)

---

## 7. Environment Variables
Create a `.env` file with the following keys:

```env
OPENAI_API_KEY=your_openai_api_key
COINBASE_API_KEY=your_coinbase_api_key
COINBASE_API_SECRET=your_coinbase_api_secret
COINGECKO_API_KEY=your_coingecko_api_key
ETHEREUM_API_URL=your_ethereum_api_endpoint
SECRET_KEY=your_secret_key
```

---

## 8. Deployment
- **Local Testing:**
  - Use Python's built-in server (`flask run` or `uvicorn` for FastAPI)
  
- **Production Deployment:**
  - Recommended services: AWS, Heroku, or Google Cloud Platform
  - Use a reverse proxy like NGINX

---

For further support, please refer to the [SolvAI Documentation](./README.md) or contact the development team.
