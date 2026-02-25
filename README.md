# LiveKit Voice Agent

## Installation

Clone or create the template:
```bash
lk app create --template agent-starter-react
```

Install dependencies:
```bash
pnpm install
```

## Environment Setup

Create `.env.local` file with:
```env
LIVEKIT_API_KEY=your_livekit_api_key
LIVEKIT_API_SECRET=your_livekit_api_secret
LIVEKIT_URL=https://your-livekit-server-url
AGENT_NAME=your_agent_name
```

## Run

```bash
pnpm dev
```

Open http://localhost:3000 in your browser.
