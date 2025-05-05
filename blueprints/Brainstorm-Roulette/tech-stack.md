# App Tech Stack

## Core Philosophy
This tech stack is designed for a solo developer to build and maintain Brainstorm Roulette, with a focus on modern, learnable technologies that provide a good balance between development speed and long-term maintainability.

## Full-Stack Framework
- **Next.js**

## Frontend
- **Language**: TypeScript (for type safety and improved developer experience)
- **Framework**: React (through Next.js) with functional components and hooks
- **State Management**: React Context API for simpler state needs
- **Styling**: Tailwind CSS
- **Canvas/Visualization**:
  - react-flow (for node-based connections and mind mapping)
  - HTML Canvas API

## Backend
- **Approach**: Next.js API routes (built into the framework)
- **Language**: TypeScript

## Data Storage
- **Client-side**: 
  - localStorage (for user session data)
  - Next.js server components for server-side state

## Containerization
- **Docker**: Single container deployment
  - Dockerfile optimized for Next.js applications
  - Multi-stage builds for smaller production images
  - Node.js runtime environment

## External APIs & Services
- **AI Integration**:
  - First mock api responses for demo
  - OpenAI API (single service to minimize complexity)

## Deployment & Hosting
- **Hosting**: Render.com Web Service with Docker support
- **Configuration**: 
  - Environment variables managed through Render.com dashboard
  - Automatic deployments from GitHub repository
- **Database**: None initially, local files in container
- **Domain**: Default subdomain provided by Render (no custom domain initially)

## Development Environment
- **Package Manager**: npm
linter? eslint, prettier

