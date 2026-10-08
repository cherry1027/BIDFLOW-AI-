# BidFlow AI

BidFlow AI is an interactive bid management and AI process optimization platform designed for industrial service tenders.

🔗 **Live Demo:** [bidflow-ai.charanvaranasi44.workers.dev](https://bidflow-ai.charanvaranasi44.workers.dev/)

## Features

### AI Bid Management

- AI-style RFQ requirement extraction and classification
- Interactive bid workflow from intake to submission
- Missing information, bottleneck, and risk detection
- Bid summaries, clarification questions, and response drafts
- Human review and approval workflow
- Requirement filtering and confidence scoring
- Exportable bid findings

### AI Efficiency & Playbook

- Interactive AI opportunity assessment matrix
- Manual versus AI-assisted effort comparison
- Adjustable bid volume and AI adoption assumptions
- Time-saving, capacity-value, and rework calculations
- Efficiency, quality, feasibility, adoption, and risk visualization
- Practical AI adoption playbook
- Interactive 30/60/90-day implementation roadmap
- Exportable recommendations

## Technology

- React
- TypeScript
- Tailwind CSS
- Lucide React
- Recharts
- Vinext/Vite
- Cloudflare Workers
- Wrangler

## Run Locally

```bash
npm install
npm run dev
```

Open the local URL displayed in the terminal.

## Production Build

```bash
npm run build
```

## Deploy to Cloudflare

Authenticate with Cloudflare:

```bash
npx wrangler login
```

Build and deploy:

```bash
npm run build
npx wrangler deploy --config dist/server/wrangler.json --name bidflow-ai
```

## Important Note

BidFlow AI is a frontend demonstration. All organizations, tenders, requirements, financial values, performance estimates, AI outputs, and efficiency calculations are fictional and simulated.

The application does not use a backend, authentication system, database, or paid API. AI-style outputs are deterministic demonstrations and require human review.
