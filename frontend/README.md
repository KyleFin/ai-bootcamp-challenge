# AI Bootcamp Challenge Frontend

This is a modern React frontend for the AI Bootcamp Challenge API, built with Next.js and Tailwind CSS.

## Features

- Real-time streaming chat interface
- Support for developer and user messages
- OpenAI API key management
- Model selection (GPT-4.1 Mini, GPT-4, GPT-3.5 Turbo)
- Responsive design
- Modern UI with Tailwind CSS

## Prerequisites

- Node.js 18.x or later
- npm or yarn
- The backend API running on http://localhost:8000

## Setup

1. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

2. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Development

The frontend is built with:
- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- Heroicons

The main components are:
- `app/page.tsx` - The main chat interface
- `app/layout.tsx` - The root layout component
- `app/globals.css` - Global styles and Tailwind configuration

## API Integration

The frontend communicates with the backend API at http://localhost:8000. Make sure the backend is running before using the frontend.

The main API endpoint used is:
- POST `/api/chat` - For sending chat messages and receiving streaming responses

## Environment Variables

No environment variables are required for local development. The API URL is hardcoded to http://localhost:8000 for simplicity.