## 🏗️ Architecture

- **Frontend**: React + TypeScript + Tailwind CSS
- **Backend**: Node.js + Express + TypeScript
- **Database**: Neon (PostgreSQL)
- **Containerization**: Docker
- **Deployment**: TBD

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- Docker & Docker Compose
- Git

### Development Setup
```bash
# Clone the repository
git clone git@github.com:Aliha103/All-Arco-Apartment.git
cd All-Arco-Apartment

# Install dependencies
npm run install:all

# Start development environment
npm run dev

# Or with Docker
docker-compose up -dev
📁 Project Structure
venice-apartment-platform/
├── frontend/          # React TypeScript application
├── backend/           # Node.js API server
├── shared/           # Shared types and utilities
├── docker/           # Docker configuration files
├── docs/             # Documentation
├── scripts/          # Build and deployment scripts
└── .github/          # GitHub Actions workflows
🛠️ Available Scripts

npm run dev - Start both frontend and backend in development mode
npm run build - Build both applications for production
npm run test - Run all tests
npm run lint - Lint all code
npm run docker:dev - Start development environment with Docker

📖 Documentation

API Documentation
Architecture Overview
Deployment Guide

🏨 Features
Phase 1 (Month 1-2)

 User authentication
 Property showcase
 Basic booking system
 Calendar availability

Phase 2 (Month 3-4)

 Payment integration
 Guest portal
 Communication system

Phase 3 (Month 5-6)

 Property management dashboard
 Analytics & reporting
 Mobile optimization

🤝 Contributing

Fork the repository
Create a feature branch (git checkout -b feature/amazing-feature)
Commit your changes (git commit -m 'Add amazing feature')
Push to the branch (git push origin feature/amazing-feature)
Open a Pull Request

📄 License
This project is private and proprietary.