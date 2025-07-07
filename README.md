# Bitcoin Wallet Explorer

Bitcoin Wallet Explorer is a web application that allows users to track Bitcoin wallet activity in real time. The application displays comprehensive details including wallet balance, total received and sent amounts, transaction history, and equivalent values in USD.

## Features

- Search by any valid Bitcoin address.
- Display wallet summary including balance, total received, total sent, and total transactions.
- Show detailed transaction history with confirmation status and timestamp.
- Display transaction amounts in BTC and their equivalent in USD using real-time data.
- Load transactions incrementally with a "Load More" button to improve performance.
- Dark and light mode toggle for comfortable viewing.
- Responsive and modern UI with smooth animations.

## Technologies Used

- **HTML5** and **CSS3** for structure and styling.
- **JavaScript (ES6+)** for interactivity and API requests.
- **Font Awesome** for icons.
- **Google Fonts (Inter)** for typography.

## APIs Used

- [BlockCypher API](https://www.blockcypher.com/dev/bitcoin/) — to fetch detailed Bitcoin address and transaction data.
- [CoinGecko API](https://www.coingecko.com/en/api) — to retrieve real-time Bitcoin price in USD for conversion.

## Design

The interface follows a clean, modern aesthetic with an emphasis on readability and usability. It features a dark mode by default, with a toggle button for switching to light mode. The design includes smooth fade and pulse animations to enhance user experience without compromising performance.

## Usage

1. Enter a valid Bitcoin wallet address into the input field.
2. Click the "Buscar Carteira" (Search Wallet) button.
3. The app will display the wallet’s summary and transaction history.
4. Click "Carregar Mais Transações" (Load More Transactions) to fetch additional transactions if available.
5. Toggle between dark and light modes using the moon/sun icon on the top right.

## License

This project is open source and available under the MIT License.

---
