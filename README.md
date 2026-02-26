saibak-racing-marketplace/
├── client/          ← React + Vite + TailwindCSS
│   └── src/
│       ├── App.jsx
│       ├── pages/   ← Home, Cars, Motos, Cart, Prompt, Heuristics, +5 más
│       ├── components/ ← Sidebar, Navbar, CarCard, LoginModal, Toast
│       ├── context/ ← AuthContext, CartContext
│       └── data/    ← 12 vehículos de carreras
└── server/          ← Node + Express + MongoDB
    ├── server.js
    ├── models/      ← User, Vehicle
    ├── routes/      ← auth, vehicles
    └── middleware/  ← JWT auth
