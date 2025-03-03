# Coyamin - AI-Powered Financial Insights

Coyamin is an AI-powered financial insights application that helps users understand and optimize their personal finances. Built with Next.js, CopilotKit for AI assistance, and Maybe Finance API for financial data.

## Features

- **Personalized Financial Dashboard**: View your financial health at a glance
- **AI Financial Assistant**: Get personalized financial advice with CopilotKit
- **Intelligent Onboarding**: Answer questions to generate tailored financial insights
- **Investment Analysis**: Visualize your investment portfolio and asset allocation
- **Currency & Market Data**: Access real-time financial market data

## Tech Stack

- **Frontend**: Next.js 14+, React, Tailwind CSS
- **AI Integration**: CopilotKit
- **Financial Data**: Maybe Finance API
- **Authentication**: Clerk
- **Visualization**: Recharts

## Installation

### Prerequisites

- Node.js 18+ and npm
- Accounts for:
  - Next Auth (authentication)
  - [CopilotKit](https://docs.copilotkit.ai/) (AI assistant)
  - [Maybe Finance](https://synthfinance.com/) (financial data API)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Tabintel\/ai-savings.git
   cd ai-savings
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file based on `.env.example`:
   ```bash
   cd .env.example .env
   ```

4. Fill in your API keys and environment variables in the `.env` file

5. Run the development server:
   ```bash
   npm run dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure

```
ai-savings
├─ app/                    # Next.js application
│  ├─ (auth)/              # Authentication routes
│  ├─ api/                 # API routes
│  │  ├─ currencies/       # Currency data endpoints
│  │  ├─ enrich/           # Financial data enrichment
│  │  └─ rates/            # Exchange rates
│  ├─ dashboard/           # Main dashboard page
│  ├─ onboarding/          # User onboarding flow
│  └─ layout.tsx           # Root layout component
├─ components/             # Shared components
├─ lib/                    # Utility functions and services
└─ public/                 # Static assets
```

## Environment Variables

See `.env.example` for required environment variables.

## Deployment

The application can be deployed on Vercel, Netlify, or any hosting service that supports Next.js.

```bash
npm run build
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.