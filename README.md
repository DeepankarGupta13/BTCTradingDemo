# Bitcoin Trading Demo

This is a simple React app that demonstrates a mock Bitcoin trading platform. It includes a live Bitcoin price chart powered by CoinGecko's API and a basic trading panel for buying and selling Bitcoin in USD.

## Features

- Live Bitcoin Price Chart
- Mock Trading Panel (Buy/Sell Bitcoin)
- Real-time price updates for Bitcoin (from CoinGecko API)

## Setup

To run this project locally, follow the steps below:

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/bitcoin-trading-demo.git
```

### 2. Install Dependencies

Navigate to the project folder and install the dependencies:

```bash
cd bitcoin-trading-demo
npm install
```

### 3. Run the App

Start the React development server:

```bash
npm start
```

This will start the app at [http://localhost:3000](http://localhost:3000).

## Folder Structure

```
src/
├── components/
│   ├── Chart.js         # Component for rendering Bitcoin price chart
│   ├── TradingPanel.js  # Component for the mock trading panel
├── App.js               # Main application component
├── index.js             # Entry point for the React app
└── App.css              # Global styles
```

## API Used

- **CoinGecko API**: Used to fetch real-time Bitcoin price data.

### API Endpoint
```
GET https://api.coingecko.com/api/v3/coins/bitcoin/market_chart?vs_currency=usd&days=1&interval=minute
```

This endpoint retrieves the last 24 hours of Bitcoin data in USD, with minute-by-minute pricing.

## License

This project is open-source and available under the [MIT License](LICENSE).
