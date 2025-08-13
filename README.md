# 3D Multiplayer Chess Game

A modern 3D chess game built with React, Three.js, and WebSocket for multiplayer functionality.
<img width="1893" height="939" alt="Screenshot 2025-08-13 213108" src="https://github.com/user-attachments/assets/5f11d3b2-8d8f-40ff-a295-76687828f364" />


## 🚀 Technologies Used

### Frontend
- **React** - UI library
- **TypeScript** - Type-safe JavaScript
- **Three.js** - 3D graphics library
- **React Three Fiber** - React renderer for Three.js
- **Socket.IO Client** - Real-time communication
- **Tailwind CSS** - Styling

### Backend
- **Node.js** - Runtime environment
- **Express** - Web framework
- **Socket.IO** - Real-time communication
- **TypeScript** - Type-safe JavaScript

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- npm (v6 or higher)
- Git

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/3d-chess.git
cd 3d-chess
```

2. Install dependencies for both frontend and backend:
```bash
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

## 🔧 Configuration

1. Create a `.env` file in the backend directory:
```env
PORT=3001
NODE_ENV=development
```

2. Create a `.env` file in the frontend directory:
```env
REACT_APP_API_URL=http://localhost:3001
```

## 🚀 Running the Application

### Development Mode

1. Start the backend server:
```bash
cd backend
npm run dev
```

2. In a new terminal, start the frontend development server:
```bash
cd frontend
npm start
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend: http://localhost:3001

### Production Build

1. Build the frontend:
```bash
cd frontend
npm run build
```

2. Start the production server:
```bash
cd backend
npm start
```

## 🎮 Game Features

- 3D chess board with realistic pieces
- Real-time multiplayer functionality
- Move validation and legal move highlighting
- Captured pieces display
- Check and checkmate detection
- Game state persistence
- Turn-based gameplay
- Camera controls for board viewing

## 📁 Project Structure

```
3d-chess/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Board.tsx
│   │   │   ├── ChessGame.tsx
│   │   │   ├── CapturedPieces.tsx
│   │   │   └── GameInfo.tsx
│   │   ├── chess/
│   │   │   ├── ChessGame.ts
│   │   │   └── types.ts
│   │   ├── three/
│   │   │   ├── three-setup.ts
│   │   │   └── models/
│   │   ├── App.tsx
│   │   └── index.tsx
│   └── package.json
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── services/
│   │   └── index.ts
│   └── package.json
└── README.md
```

## 🎯 Game Rules Implementation

The chess game implements standard chess rules including:
- Piece movement validation
- Check detection
- Checkmate detection
- Stalemate detection
- Special moves (castling, en passant)
- Turn management
- Captured pieces tracking

## 🔄 Multiplayer Features

- Real-time game state synchronization
- Player matching
- Game room management
- Disconnect handling
- Move validation on server
- Game state persistence

## 🎨 3D Features

- Realistic 3D chess pieces
- Dynamic camera controls
- Lighting and shadows
- Material effects
- Smooth animations
- Board and piece highlighting

## 🛠️ Development Workflow

1. **Setting up the development environment**
   - Install all dependencies
   - Configure environment variables
   - Start development servers

2. **Making changes**
   - Frontend changes will hot-reload
   - Backend changes will restart the server
   - Use TypeScript for type safety

3. **Testing**
   - Run frontend tests: `npm test` in frontend directory
   - Run backend tests: `npm test` in backend directory

4. **Building for production**
   - Build frontend: `npm run build` in frontend directory
   - Start production server: `npm start` in backend directory

## 📝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Three.js community for 3D graphics support
- React Three Fiber for React integration
- Socket.IO for real-time communication
- Chess.js for chess logic reference

## 🆘 Support

For support, please open an issue in the GitHub repository or contact the maintainers.

## 🔄 Updates

Check the repository regularly for updates and new features. Follow the changelog for detailed information about changes. 
