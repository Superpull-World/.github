# SuperPull: Decentralized Fashion Marketplace

SuperPull is a decentralized fashion marketplace built on Solana, enabling emerging designers to connect with collectors through innovative bonding curve auctions and compressed NFTs.

## 🌟 Key Features

- **Bonding Curve Auctions**: Fair price discovery and distribution
- **Compressed NFTs**: Cost-efficient digital fashion assets
- **Mobile-First**: Beautiful Flutter app for seamless interaction
- **Automated Market Making**: Continuous liquidity for fashion NFTs

## 🏗️ Architecture

The project consists of three main components:

### 1. SuperPull Program [`https://github.com/Superpull-World/program`]
A Solana program implementing bonding curve auctions for compressed NFTs.
- Linear bonding curve for predictable pricing
- 99.99% cost reduction using compressed NFTs
- Secure and efficient on-chain logic

### 2. SuperPull Services [`https://github.com/Superpull-World/services`]
Backend services powering the marketplace.
- RESTful API for marketplace interactions
- Solana transaction handling
- Metadata management and caching
- Workflow orchestration

### 3. SuperPull Mobile [`https://github.com/Superpull-World/mobile`]
Flutter-based mobile application.
- Modern and intuitive UI
- Integrated Solana wallet
- Real-time price updates
- Seamless NFT minting experience

## 💡 Innovation

### Bonding Curve Implementation
```
current_price = base_price + (price_increment * current_supply)
```
- Transparent and predictable pricing
- Early supporters get better prices
- Automated price discovery
- Continuous market liquidity

### Compressed NFTs
- Traditional NFT: ~0.012 SOL per mint
- Compressed NFT: ~0.000001 SOL per mint
- 99.99% cost reduction
- Scalable for large collections

## 🚀 Getting Started

### Prerequisites
- Solana Tool Suite
- Node.js and npm
- Flutter SDK
- Anchor Framework

### Quick Start
1. Clone the repository:
```bash
git clone https://github.com/yourusername/superpull.git
cd superpull
```

2. Set up the program:
```bash
cd program
anchor build
anchor deploy
```

3. Start the services:
```bash
cd services
npm install
npm run dev
```

4. Run the mobile app:
```bash
cd mobile
flutter pub get
flutter run
```

## 📱 Mobile App Preview

[Screenshots coming soon]

## 🔗 Architecture Diagram

```
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│  Mobile App     │     │    Services      │     │  Solana Program │
│  (Flutter)      │────▶│    (Node.js)     │────▶│  (Rust/Anchor)  │
└─────────────────┘     └─────────────────┘     └─────────────────┘
        │                       │                        │
        │                       │                        │
        ▼                       ▼                        ▼
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│   Local Wallet  │     │  State Cache    │     │   Blockchain    │
└─────────────────┘     └─────────────────┘     └─────────────────┘
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

## 🔗 Links

- [Documentation](docs/)
- [API Reference](api-docs/)
- [Mobile App](https://play.google.com/store/...)
- [Discord Community](https://discord.gg/...)

## 🌟 Support

If you like this project, please give it a star ⭐️

## 📫 Contact

- Email: support@superpull.xyz
- Twitter: [@SuperPull](https://twitter.com/superpull)
- Discord: [Join our community](https://discord.gg/superpull) 
