# ChainScholar

> Where Privacy & Trust Redefine Research - Revolutionizing Scientific Collaboration with Blockchain Technology

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status: In Development](https://img.shields.io/badge/Status-In%20Development-orange)](https://github.com/lisakyoung/chainscholar)

## 🚀 Overview

ChainScholar is a blockchain-based research platform that solves the fundamental tension between transparency and privacy in scientific collaboration. By leveraging cutting-edge blockchain technology, we enable researchers to share, verify, and collaborate on sensitive data while maintaining complete control over their intellectual property.

### Key Features

- 🔐 **Privacy-Preserving Research**: Granular access control for sensitive datasets
- ✅ **Fraud-Proof Verification**: Cryptographically guaranteed data integrity
- 🤝 **Secure Collaboration**: Share research with specific institutions or researchers
- 🧠 **AI-Powered Discovery**: Machine learning enhances research connections
- 💰 **Fair Monetization**: Researchers control and monetize their contributions

## 🛠️ Technology Stack

### Blockchain

- **Sui Blockchain** - High-performance Layer 1 blockchain
- **Move Language** - Resource-oriented smart contract programming
- **Calimero Network** - Privacy layer for selective data sharing

### Frontend

- **Next.js 14** - React framework with App Router
- **TypeScript** - Type-safe JavaScript
- **TailwindCSS** - Utility-first CSS framework
- **Sui.js** - Sui blockchain JavaScript SDK

### Backend

- **Rust** - High-performance system programming
- **PostgreSQL** - Primary database
- **Redis** - Caching and real-time operations
- **Docker/Kubernetes** - Containerization and orchestration

## 📁 Project Structure

```
chainscholar/
├── apps/
│   ├── web/                 # Next.js frontend application
│   └── api/                 # Rust backend API
├── packages/
│   ├── contracts/           # Move smart contracts
│   ├── sdk/                 # TypeScript SDK
│   └── ui/                  # Shared UI components
├── docs/                    # Documentation
├── scripts/                 # Development and deployment scripts
└── docker/                  # Docker configurations
```

## 🚦 Getting Started

### Prerequisites

- Node.js 18+ and pnpm
- Rust 1.70+
- Docker and Docker Compose
- Sui CLI tools

### Installation

1. Clone the repository:

```bash
git clone https://github.com/lisakyoung/chainscholar.git
cd chainscholar
```

2. Install dependencies:

```bash
pnpm install
```

3. Set up environment variables:

```bash
cp .env.example .env.local
# Edit .env.local with your configuration
```

4. Start development servers:

```bash
pnpm dev
```

## 🧪 Development

### Running Tests

```bash
pnpm test                    # Run all tests
pnpm test:unit              # Run unit tests
pnpm test:integration       # Run integration tests
```

### Code Quality

```bash
pnpm lint                   # Run ESLint
pnpm format                 # Format code with Prettier
pnpm typecheck             # Run TypeScript checks
```

### Building for Production

```bash
pnpm build                  # Build all packages
pnpm build:web             # Build frontend only
pnpm build:contracts       # Compile Move contracts
```

## 📊 Project Status

### Current Phase: MVP Development (Phase 1)

- [x] System architecture design
- [x] Technology stack selection
- [ ] Core smart contract development
- [ ] Frontend UI framework
- [ ] Backend API development
- [ ] Integration testing

### Roadmap

- **Q2 2024**: Core platform development
- **Q3 2024**: Privacy features & security audit
- **Q4 2024**: Beta testing with research institutions
- **December 2024**: Public launch

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Process

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- [Website](https://chainscholar.io) (Coming Soon)
- [Documentation](https://docs.chainscholar.io) (Coming Soon)
- [Discord Community](https://discord.gg/chainscholar) (Coming Soon)

## 👥 Team

- **Dahyun (Lisa) Kyoung** - Project Lead - [@lisakyoung](https://github.com/lisakyoung)

## 📞 Contact

For questions or partnerships, reach out at: hello@chainscholar.io

---

<p align="center">
  Built with ❤️ for the future of decentralized science
</p>
