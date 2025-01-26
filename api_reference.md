# API Reference  

This document provides an overview of the APIs integrated into the SolvAI platform and how they are utilized to deliver its features.  

---

## **APIs Used in SolvAI**  

### 1. **OpenAI API**  
- **Purpose**: Powers the natural language processing (NLP) and conversational abilities of the SolvAI AI Agent.  
- **Features Enabled**:  
  - Chat with AI Agent for crypto advice and insights.  
  - Generate personalized responses to user queries.  
  - Analyze and summarize ICO and yield farming data.  
- **Endpoints Used**:  
  - `POST /v1/chat/completions` – To generate chat-based responses.  
  - `POST /v1/completions` – For text-based predictions or recommendations.  
- **Documentation**: [OpenAI API Docs](https://platform.openai.com/docs/)  

---

### 2. **Coinbase API**  
- **Purpose**: Provides cryptocurrency market data and enables crypto price tracking.  
- **Features Enabled**:  
  - Fetching real-time cryptocurrency prices and market trends.  
  - Supporting user portfolio tracking and analytics.  
- **Endpoints Used**:  
  - `GET /prices/{crypto}-{currency}/spot` – Fetch current spot price for cryptocurrencies.  
  - `GET /currencies` – Retrieve a list of supported currencies.  
- **Documentation**: [Coinbase API Docs](https://developers.coinbase.com/)  

---

### 3. **CoinGecko API**  
- **Purpose**: Delivers comprehensive market data, including ICOs, yield farming opportunities, and token details.  
- **Features Enabled**:  
  - Discovering new ICOs and trending tokens.  
  - Providing detailed information about tokens, including volume and market cap.  
  - Displaying historical price data for in-depth analysis.  
- **Endpoints Used**:  
  - `GET /coins/list` – Retrieve a list of all supported coins.  
  - `GET /coins/{id}` – Fetch detailed coin data, including market information.  
  - `GET /simple/price` – Get current price data for specified cryptocurrencies.  
- **Documentation**: [CoinGecko API Docs](https://www.coingecko.com/en/api/documentation)  

---

### 4. **Ethereum API (via Web3.js)**  
- **Purpose**: Enables blockchain interactions for SolvAI’s token ($SOLVAI) ecosystem and other Ethereum-based operations.  
- **Features Enabled**:  
  - Managing $SOLVAI token-related transactions.  
  - Verifying wallet addresses and balances.  
  - Tracking gas fees and transaction statuses.  
- **Endpoints Used**:  
  - `eth_getBalance` – Check the balance of a given Ethereum address.  
  - `eth_sendTransaction` – Submit transactions to the Ethereum network.  
  - `eth_call` – Interact with smart contracts.  
- **Documentation**: [Ethereum Web3.js Docs](https://web3js.readthedocs.io/en/v1.7.0/)  

---

## **Integration Overview**  

Below is a table summarizing the key APIs and their roles in the SolvAI ecosystem:  

| API         | Purpose                                    | Key Features                                          | Documentation Link                        |  
|-------------|--------------------------------------------|------------------------------------------------------|-------------------------------------------|  
| OpenAI      | NLP and conversational AI                 | AI Agent responses, query analysis, text generation | [OpenAI Docs](https://platform.openai.com/docs/) |  
| Coinbase    | Market data and price tracking            | Real-time crypto prices, portfolio analysis         | [Coinbase Docs](https://developers.coinbase.com/) |  
| CoinGecko   | Comprehensive crypto market data          | ICOs, yield farming opportunities, token analysis   | [CoinGecko Docs](https://www.coingecko.com/en/api/documentation) |  
| Ethereum    | Blockchain interactions and token utility | $SOLVAI transactions, wallet verification           | [Web3.js Docs](https://web3js.readthedocs.io/en/v1.7.0/) |  

---

## **How to Use the APIs in SolvAI**  
SolvAI connects to these APIs via secure endpoints to provide a seamless user experience. If you’d like to contribute or test SolvAI features:  
1. Clone the repository.  
2. Add your API keys to the `.env` file:  
   ```env  
   OPENAI_API_KEY=your_openai_api_key  
   COINBASE_API_KEY=your_coinbase_api_key  
   COINGECKO_API_KEY=your_coingecko_api_key  
   INFURA_PROJECT_ID=your_infura_project_id  
   ```  
3. Follow the instructions in the `README.md` file to set up and run the project.  

---

## **Future Plans**  
SolvAI aims to expand API integrations to include:  
- Binance API for advanced trading data.  
- DeFi protocols for on-chain yield farming analytics.  
- Advanced AI frameworks for more personalized responses.  

---  

For more information or support, visit our [GitHub Repository](https://github.com/your-repo-link) or contact us at [support@solvai.com](mailto:support@solvai.com).  
