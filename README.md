# MERN Stack with NestJS

A modern full-stack application using MongoDB, React, and NestJS with pnpm workspace.

## Tech Stack

### Backend
- **NestJS** - Progressive Node.js framework
- **MongoDB** - NoSQL database via Mongoose
- **TypeScript** - Type-safe development
- **Vitest** - Fast unit testing

### Frontend
- **React 19** - UI library
- **TypeScript** - Type-safe development
- **Vite** - Fast build tool
- **ESLint** - Code linting

## Project Structure

```
nest-react-app/
├── backend/           # NestJS API server
│   ├── src/
│   └── package.json
├── frontend/          # React application
│   ├── src/
│   └── package.json
├── package.json       # Root workspace config
└── pnpm-workspace.yaml
```

## Prerequisites

- Node.js (v18 or higher)
- pnpm (v8 or higher)
- MongoDB

## Installation

```bash
# Install dependencies for all workspaces
pnpm install
```

## Development

```bash
# Start backend development server
cd backend
pnpm start:dev

# Start frontend development server (in another terminal)
cd frontend
pnpm dev
```

## Build

```bash
# Build backend
cd backend
pnpm build

# Build frontend
cd frontend
pnpm build
```

## Testing

```bash
# Run backend tests
cd backend
pnpm test

# Run backend tests in watch mode
cd backend
pnpm test:watch
```

## Environment Variables

Create a `.env` file in the backend directory:

```
MONGODB_URI=mongodb://localhost:27017/your-database
PORT=3000
```

## License

ISC
