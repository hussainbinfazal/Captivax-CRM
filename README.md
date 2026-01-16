# Captivax

A full-stack web application with separate Frontend and Backend directories.

## Project Structure

```
Captivax/
├── Frontend/          # React + Vite frontend application
├── Backend/           # Node.js backend server
├── .gitignore         # Git ignore rules for the entire project
└── README.md          # This file
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Captivax
   ```

2. **Install Backend dependencies**
   ```bash
   cd Backend
   npm install
   cd ..
   ```

3. **Install Frontend dependencies**
   ```bash
   cd Frontend
   npm install
   cd ..
   ```

## Running the Application

### Start Backend Server

```bash
cd Backend
npm start
# or
node server.js
```

The backend server will run on `http://localhost:3000` (or check your `server.js` for the configured port).

### Start Frontend Development Server

```bash
cd Frontend
npm run dev
```

The frontend will run on `http://localhost:5173` (Vite default port).

## Project Overview

### Backend

- **Location:** `./Backend/`
- **Technology:** Node.js
- **Main File:** `server.js`
- **Purpose:** RESTful API server handling business logic and data management

**Key Files:**
- `package.json` - Backend dependencies and scripts
- `server.js` - Main server entry point

### Frontend

- **Location:** `./Frontend/`
- **Technology:** React + Vite
- **Build Tool:** Vite
- **Purpose:** User interface and client-side application

**Key Files:**
- `package.json` - Frontend dependencies and scripts
- `vite.config.js` - Vite configuration
- `src/` - Source code (components, styles, etc.)
- `public/` - Static assets
- `index.html` - HTML entry point

## Available Scripts

### Backend

- `npm start` - Start the server
- `npm run dev` - Start development server (if configured)

### Frontend

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint checks

## Environment Variables

Create `.env` files in respective directories if needed:

- `Backend/.env` - Backend environment variables (database URLs, API keys, etc.)
- `Frontend/.env` - Frontend environment variables (API endpoints, etc.)

## Build for Production

### Backend

```bash
cd Backend
npm run build  # if build script is configured
```

### Frontend

```bash
cd Frontend
npm run build
```

Production files will be generated in `Frontend/dist/`

## Contributing

1. Create a feature branch
2. Make your changes
3. Commit with clear messages
4. Push to the repository
5. Create a Pull Request

## License

[Add your license information here]

## Support

For issues or questions, please open an issue in the repository.
