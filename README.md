# 🎲 Game Night Scheduler

> Solving the "too many people showed up" problem, one game night at a time.

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Built with AI](https://img.shields.io/badge/Built%20with-AI%20Assistance-purple)](https://claude.ai)
[![Status](https://img.shields.io/badge/Status-In%20Development-yellow)](https://gamenight.benloe.com)

## The Problem

Board games have specific player counts. When you send an open invite for game night:
- 📈 Too many people show up → Someone sits out awkwardly
- 📉 Too few people show up → Can't play the planned game
- 🎯 Board game cafes need exact table sizes for reservations
- 😬 Social dynamics get weird when choosing who plays

## The Solution

**Commitment-based scheduling** where players commit to specific games on specific dates:
- ✅ Propose a game night with exact player requirements
- ✅ Others commit to that specific event
- ✅ Event closes when full (with optional waitlist)
- ✅ Everyone knows exactly what they're signing up for

## Tech Stack

Built with modern web technologies and AI-assisted development:

- **Frontend**: React + TypeScript + Vite
- **Backend**: Node.js + Express + TypeScript  
- **Database**: SQLite + Prisma ORM
- **Styling**: Tailwind CSS + Headless UI
- **Deployment**: Self-hosted on [benloe.com](https://benloe.com)

## Features

### Core Functionality
- 🎮 **Game Database** - Search games with player count requirements
- 📅 **Event Creation** - Propose game nights with specific dates/games
- 🤝 **Commitment System** - Join events with enforced player limits
- 📱 **Mobile First** - Designed for on-the-go coordination

### Coming Soon
- 🏆 Reliability scores for consistent attendees
- 🔔 Notifications for event updates
- 🎯 Game recommendations based on group size
- 📸 Photo sharing from past game nights

## Development

This is an experimental project built with AI assistance (Claude) as part of my journey learning to build in public. The codebase emphasizes:

- **Type Safety** - TypeScript throughout for better AI code generation
- **Clear Architecture** - Dependency-driven build order
- **Rapid Iteration** - Direct deployment for quick experiments

### Local Development

```bash
# Clone the repository
git clone https://github.com/BLoe/benloe-gamenight.git
cd benloe-gamenight

# Install dependencies
npm install

# Set up database
npx prisma migrate dev

# Run development server
npm run dev
```

### Project Structure

```
/var/apps/gamenight.benloe.com/
├── server/          # Express API
├── client/          # React app
├── prisma/          # Database schema
├── shared/          # Shared types
└── CLAUDE.md        # AI context & planning
```

## Philosophy

This project is part of my experimental web development journey after 15+ years in enterprise tech. It's about:

- 🚀 **Learning by Building** - Practical solutions to real problems
- 🤖 **AI-Assisted Development** - Exploring the future of coding
- 📖 **Building in Public** - Sharing the journey, not just the destination
- 🎯 **Solving Real Problems** - Tools that actually get used

## Contributing

While this is primarily a personal learning project, I welcome:
- 🐛 Bug reports
- 💡 Feature suggestions  
- 🎮 Game database improvements
- 📚 Learning resources

## License

MIT License - See [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with assistance from [Claude](https://claude.ai)
- Inspired by countless awkward "who's playing?" moments
- Powered by the board game community's need for better coordination

---

**Live at**: [gamenight.benloe.com](https://gamenight.benloe.com) (coming soon)  
**Portfolio**: [benloe.com](https://benloe.com)  
**Contact**: Ben Loe ([GitHub](https://github.com/BLoe))

*Building & Learning in Public* 🎲