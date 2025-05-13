# TokenAI - Solana Token Analysis Platform

![TokenAI](https://img.shields.io/badge/TokenAI-Solana%20Analytics-blueviolet)
![React](https://img.shields.io/badge/React-18-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![Express](https://img.shields.io/badge/Express-4-green)
![License](https://img.shields.io/badge/License-MIT-orange)

TokenAI is a comprehensive analysis platform for Solana tokens that provides real-time data, charts, and insights for crypto traders and enthusiasts. The application features an interactive 3D interface, chatbot-driven queries, and detailed token metrics.

## 🚀 Features

- **Interactive Chatbot Interface**: Enter Solana token addresses through a conversational UI
- **Comprehensive Token Data**: View market cap, price, volume, and other key metrics
- **Real-time Price Charts**: Visualize token performance with dynamic charts
- **Social Media Integration**: Direct links to token social media channels
- **Raydium Pool Analysis**: Status indicators for token pool bonding
- **Token Age Tracking**: Launch time and age calculation for tokens
- **Responsive Design**: Optimized for both desktop and mobile devices
- **3D Visual Elements**: Modern interface with Three.js animations

## 📋 Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- An internet connection for API access

## 🛠️ Installation

### Clone the repository

```bash
git clone https://github.com/tokietoken/tokietoken.git
cd tokenai
```

### Frontend Setup

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

### Backend Setup

```bash
# Navigate to server directory
cd server

# Install dependencies
npm install

# Start server in development mode
npm run dev
```

## 🔧 Configuration

Create a `.env` file in the server directory:

```
PORT=3001
RATE_LIMIT_WINDOW_MS=60000
RATE_LIMIT_MAX=100
```

## 🖥️ Usage

1. Start both the frontend and backend servers
2. Open your browser to `http://localhost:5173`
3. Use the chatbot to enter a Solana token address
4. View comprehensive token data and analytics
5. Explore price charts and social media links


## 🏗️ Project Structure

```
tokenai/
├── src/                  # Frontend source files
│   ├── components/       # React components
│   ├── types/            # TypeScript type definitions
│   ├── utils/            # Utility functions
│   └── App.tsx           # Main application component
├── server/               # Backend server
│   ├── utils/            # Server utilities
│   └── index.ts          # Express server setup
└── public/               # Static assets
```

## 🔒 Security Features

- Token address validation with regex patterns
- Rate limiting for API requests
- Response caching to reduce API load
- CORS protection via proxy server

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- [React Three Fiber](https://github.com/pmndrs/react-three-fiber) for 3D visualizations
- [Pump.fun API](https://frontend-api.pump.fun) for token data
- [Framer Motion](https://www.framer.com/motion/) for animations

