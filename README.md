# 🎮 City Bomber - Retro Arcade Game

A classic VIC-20 inspired city bomber game built with HTML5 Canvas and JavaScript. Destroy buildings, avoid hitting the ground, and shoot the gorilla for bonus points!

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Canvas](https://img.shields.io/badge/Canvas-00599C?logo=html5&logoColor=white)

## 🎯 Game Features

| Feature | Description |
|---------|-------------|
| **Airplane** | Flies across screen, drops one level each pass |
| **Buildings** | Random heights, windows light up |
| **Gorilla** | Walks on buildings, bonus points when shot |
| **Scoring** | 10 pts per hit, 100 pts for destroyed building, 500 pts for gorilla |
| **High Scores** | Top 10 scores saved locally |
| **Responsive** | Works in any modern browser |

## 🕹️ How to Play

1. **Open `index.html`** in your browser
2. **Click anywhere** on the game canvas to drop a bomb
3. **Press SPACEBAR** to drop bombs from the plane
4. **Destroy all buildings** to advance to the next level
5. **Shoot the gorilla** for 500 bonus points
6. **Don't hit the ground** or it's game over!

## 🎮 Controls

| Control | Action |
|---------|--------|
| **Mouse Click** | Drop bomb at click location |
| **Spacebar** | Drop bomb from plane |

## 🏆 Scoring System

| Target | Points |
|--------|--------|
| Building hit | 10 pts |
| Building destroyed | 100 pts |
| Gorilla shot | 500 pts |
| Level complete | 1000 pts |

## 📁 Project Structure

```
city-bomber-game/
├── index.html      # Main game file
├── README.md       # This file
└── screenshot.png  # Game screenshot (add yours)
```

## 🛠️ Tech Stack

- **HTML5 Canvas** - Game rendering
- **JavaScript** - Game logic
- **LocalStorage** - High score persistence
- **CSS3** - Styling and animations

## 🚀 Quick Start

### Play Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/pythonandyou/city-bomber-game.git
   cd city-bomber-game
   ```

2. Open `index.html` in your browser:
   - Double-click the file, OR
   - Run a local server: `python3 -m http.server 8000`
   - Navigate to `http://localhost:8000`

### Deploy to GitHub Pages

1. Push to GitHub
2. Go to repository Settings → Pages
3. Select source: `main` branch
4. Your game will be live at: `https://pythonandyou.github.io/city-bomber-game/`

## 💡 Skills Demonstrated

This project showcases:

| Skill | Application |
|-------|-------------|
| **Canvas Animation** | Smooth game rendering |
| **Game Loop** | RequestAnimationFrame |
| **Collision Detection** | Object intersection |
| **State Management** | Game states, scores |
| **Local Storage** | Persistent high scores |
| **Event Handling** | Keyboard, mouse input |
| **Responsive Design** | Flexible canvas |

## 🎨 Customization

Want to modify the game? Here are some ideas:

- **Change colors** - Edit the CSS variables
- **Adjust difficulty** - Modify plane speed, bomb speed
- **Add power-ups** - Extra bombs, slow motion
- **Add sound effects** - Use Web Audio API
- **Add levels** - Different building patterns

## 📝 Future Enhancements

- [ ] Sound effects
- [ ] Multiple levels with increasing difficulty
- [ ] Power-ups (extra bombs, shields)
- [ ] Mobile touch controls
- [ ] Online leaderboard

## 👤 Author

**pythonandyou** - [GitHub](https://github.com/pythonandyou)

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with ❤️ for retro gaming enthusiasts*