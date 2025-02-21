# Hearthpedia Documentation

## Project Structure
```
hearthpedia/
├── client/             # React + TypeScript frontend
│   ├── src/           # Frontend source code
│   └── dist/          # Built frontend files
├── server/            # Node.js + Express backend
│   ├── src/
│   │   ├── controllers/  # Route handlers
│   │   ├── routes/      # API endpoint definitions
│   │   ├── models/      # Database models
│   │   ├── services/    # Business logic
│   │   ├── types/       # TypeScript type definitions
│   │   └── index.ts     # Server entry point
│   └── dist/          # Built backend files
├── shared/            # Shared types/utilities
└── docs/             # Additional documentation

## Key Dependencies
### Frontend
- Vite: Build tool and dev server
- React Query: Server state management
- Axios: HTTP client
- React Router: Client-side routing

### Backend
- Express: Web framework
- PostgreSQL: Database
- ts-node-dev: TypeScript development server

## Configuration Files
- `tsconfig.json`: Present in both client/ and server/ for TypeScript configuration
- `.gitignore`: Excludes node_modules, dist, env files, and logs
