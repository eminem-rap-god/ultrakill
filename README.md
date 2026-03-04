# ULTRAMURDER - FPS Game

A fast-paced, retro-style first-person shooter inspired by ULTRAKILL, built with Three.js and JavaScript.

## 🎮 Features

- **Fast-Paced Gameplay**: Quick movement and combat mechanics
- **Multiple Weapons**: Cycle through PISTOL, SHOTGUN, and ROCKET launchers
- **Enemy AI**: Intelligent enemies that chase and attack the player
- **Health & Score System**: Track your health and earn points by defeating enemies
- **Smooth FPS Controls**: WASD movement with mouse look
- **Retro Aesthetic**: Dark, minimalist visual style
- **Real-time Rendering**: Built with Three.js for smooth 3D graphics

## 🚀 How to Play

### Controls
- **WASD** - Move forward, left, backward, right
- **SPACE** - Jump
- **Mouse** - Look around (click game to lock pointer)
- **Left Click** - Shoot
- **E** - Cycle through weapons

### Weapons
1. **PISTOL** - Fast fire rate, 10 damage per shot
2. **SHOTGUN** - Slower fire rate, 25 damage per shot
3. **ROCKET** - Slowest fire rate, 50 damage per shot

### Gameplay
- Defeat enemies to earn **100 points** per kill
- New enemies spawn as you defeat them
- Avoid taking damage from enemies
- Game ends when your health reaches 0

## 📁 Project Structure

```
ultramurder/
├── index.html          # Complete game in a single HTML file
├── README.md           # This file
└── (Additional files to come)
```

## 🛠️ Technologies Used

- **Three.js** - 3D graphics library
- **JavaScript** - Game logic
- **HTML5** - Markup
- **CSS3** - Styling

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/eminem-rap-god/ultramurder.git
   ```

2. Open `index.html` in your web browser

3. Click to start playing!

## 🎯 Game Mechanics

### Player
- Health: 100 HP
- Movement Speed: Variable with momentum
- Jump Height: Fixed power
- Weapon Switching: Press E to cycle

### Enemies
- Spawn in waves
- Chase player when detected
- Deal 0.1 damage per frame on contact
- Drop when health reaches 0

### Arena
- 500x500 unit play area
- Surrounded by walls
- Ground with physics

## 🔮 Future Features

- [ ] Advanced weapon mechanics (ammo system)
- [ ] More enemy types
- [ ] Power-ups and upgrades
- [ ] Level progression
- [ ] Sound effects and music
- [ ] Particle effects (blood, explosions)
- [ ] Difficulty settings
- [ ] Leaderboard system
- [ ] Mobile/touch controls
- [ ] Multiplayer (WebSocket)

## 🐛 Known Issues

- Enemy pathfinding is basic (direct line to player)
- No obstacle avoidance for enemies
- Raycast detection could be more accurate
- No reload mechanic yet

## 📝 License

MIT License - Feel free to use and modify this project!

## 👾 Credits

- Inspired by **ULTRAKILL** by Hakita
- Built with **Three.js**
- Developed by eminem-rap-god

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

For questions or suggestions, feel free to open an issue on GitHub!

---

**Play ULTRAMURDER**: [Open Game](https://eminem-rap-god.github.io/ultramurder/)
