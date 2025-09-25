# Plinko Game 🎯

A fun and interactive **Plinko Game** built with **React, TypeScript, and Node.js**, where players drop balls into a board of pegs and watch them bounce into slots.

## Features
- Interactive Plinko board with bouncing ball animation.
- Real-time scoring system with backend support.
- Smooth physics-based movement for realistic gameplay.
- Responsive design for desktop and mobile.

## Tech Stack
- **Frontend**: React, TypeScript, Tailwind CSS  
- **Backend**: Node.js, Express  
- **Game Logic**: Custom physics & animation using TypeScript  

---

## Getting Started 🚀

### 1. Clone the Repository
```sh
git clone https://github.com/sanketkharat28/playPlinko
cd playPlinko

### 2. Install Dependencies
Backend:
```sh
cd backend
npm install
```

Frontend:
```sh
cd frontend
npm install
```

### 3. Run the Application
Start Backend Server:
```sh
cd backend
npm run build
npm start
```

Start Frontend:
```sh
cd frontend
npm run dev
```

Backend will run at: http://localhost:8080

Frontend will run at: http://localhost:5173

## How It Works ⚡

Player clicks to drop a ball from the top of the Plinko board.

The ball bounces off pegs as it falls, changing direction randomly.

The backend handles scoring logic and updates the results.

The frontend displays animations and score updates in real-time.