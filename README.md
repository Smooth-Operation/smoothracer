# SmoothRacer

A 2D physics-based trail racing game inspired by Hill Climb Racing, featuring procedurally generated terrain and competitive leaderboards.

## About

SmoothRacer challenges players to navigate treacherous, randomly generated terrain while managing fuel, vehicle physics, and ever-changing environmental conditions. No two runs are the same - each race presents a unique combination of surfaces, weather, and altitude changes.

## Features

### Procedural Terrain Generation
- **Random surfaces** - dirt, mud, ice, sand, asphalt, and more
- **Dynamic weather** - rain, snow, fog affecting vehicle handling
- **Altitude variations** - hills, valleys, and steep climbs
- **Obstacles** - rocks, jumps, and hazards scattered throughout

### Gameplay
- Physics-based vehicle controls with realistic handling
- Distance-based scoring system
- Score converts to in-game currency
- Multiple vehicles to unlock and upgrade
- Endless runner format - go as far as you can

### Competitive Features
- Global leaderboards
- Personal best tracking
- Player rankings and stats

### Progression System
- Earn currency based on distance traveled
- Unlock new vehicles
- Purchase upgrades and customizations
- Persistent inventory across sessions

## Tech Stack

- **Frontend**: Web-based 2D game engine
- **Backend**: Supabase
  - Authentication (player accounts)
  - Database (leaderboards, stats, inventory)
  - Real-time updates for leaderboards

## Getting Started

```bash
# Clone the repository
git clone <repository-url>

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Add your Supabase credentials

# Run development server
npm run dev
```

## Environment Variables

```
SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_supabase_anon_key
```

## Database Schema

### Players
- User profile and authentication
- Currency balance
- Total distance traveled
- Games played

### Leaderboards
- Global high scores
- Daily/weekly rankings
- Personal records

### Inventory
- Owned vehicles
- Purchased upgrades
- Cosmetic items

## License

MIT
