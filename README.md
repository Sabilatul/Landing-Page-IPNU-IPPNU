NAMA : SABILATUL HANIK
NIM : 101230066
KELAS : TF23C
# Landing Page IPNU-IPPNU

Repository: https://github.com/Sabilatul/Landing-Page-IPNU-IPPNU

## Project Overview

This repository contains the source code for the IPNU-IPPNU landing page and supporting backend API.
The project is built with Vite, React, and modern UI tooling.

The design is based on the original Figma project:
https://www.figma.com/design/zd1SzvJhR6bjx85UFqljCO/Landing-page-IPNU-IPPNU

## Tech Stack

- Frontend: Vite, React, Tailwind CSS, MUI, Radix UI
- Backend: Express, MySQL, CORS, dotenv
- Tooling: npm, nodemon

## Prerequisites

- Node.js installed
- npm or pnpm installed
- For backend database support: MySQL / XAMPP (optional if using backend features)

## Frontend Setup

1. Install frontend dependencies:

```bash
npm install
```

2. Start the frontend development server:

```bash
npm run dev
```

3. Open the local URL shown in the terminal (typically `http://localhost:5173`).

## Backend Setup

The backend service lives inside the `backend/` folder and provides member registration APIs.

1. Install backend dependencies:

```bash
cd backend
npm install
```

2. Start the backend server:

```bash
npm run dev
```

3. The backend server runs on `http://localhost:3001` by default.

## Backend Notes

- Backend entry file: `backend/src/server.js`
- Database config and routes are in `backend/src/config` and `backend/src/routes`
- For database setup instructions, see `backend/README.md`

## Repository Structure

- `src/` - Frontend source code
- `backend/` - Backend server source code
- `backend/database.sql` - MySQL schema for backend data
- `package.json` - Frontend package metadata and scripts
- `backend/package.json` - Backend package metadata and scripts
- `vite.config.ts` - Vite configuration

## Useful Commands

- `npm install` - install frontend dependencies
- `npm run dev` - run frontend
- `cd backend && npm install` - install backend dependencies
- `cd backend && npm run dev` - run backend with nodemon

## Additional Resources

- Frontend design reference: Figma
- Backend database guide: `backend/README.md`
  
