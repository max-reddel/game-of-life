# Conway's Game of Life

A modern, interactive implementation of Conway's Game of Life with a beautiful glowing aesthetic and intuitive controls.

![Game of Life Demo](https://img.shields.io/badge/demo-live-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![JavaScript](https://img.shields.io/badge/javascript-vanilla-yellow)

## 🎮 Live Demo

[Try it live here](https://yourusername.github.io/game-of-life/) <!-- Update with your actual GitHub Pages URL -->

## ✨ Features

- **Interactive Grid**: Click to create life, drag to draw patterns
- **Smooth Controls**: Pan with Shift+drag, zoom with mouse wheel
- **Classic Patterns**: Pre-loaded patterns including Glider, Gosper Gun, Pulsar, and more
- **Mega Factory**: A complex 150x100 pattern with multiple interacting components
- **Speed Control**: Adjustable simulation speed from 1 to 128 generations per second
- **Real-time Stats**: Live generation and population counters
- **Beautiful Design**: Glowing green cells on a dark background
- **Responsive**: Works on all screen sizes

## 🎯 How to Play

1. **Draw Cells**: Click on the grid to toggle cells alive/dead
2. **Pan Around**: Hold Shift and drag to move around the large 300x200 grid
3. **Zoom**: Use your mouse wheel to zoom in/out
4. **Run Simulation**: Click Play/Pause to start or pause the evolution
5. **Reset**: Return to your original pattern after experimenting
6. **Load Patterns**: Choose from classic patterns in the dropdown

## 📐 Rules

Conway's Game of Life follows four simple rules:

1. Any live cell with 2 or 3 live neighbors survives
2. Any dead cell with exactly 3 live neighbors becomes alive
3. All other live cells die in the next generation
4. All other dead cells stay dead

## 🛠️ Technical Details

- **Pure Vanilla JavaScript**: No frameworks or dependencies
- **HTML5 Canvas**: Hardware-accelerated rendering
- **Optimized Performance**: Only renders visible cells
- **Grid Size**: 300×200 cells (60,000 total cells)
- **Zoom Range**: 0.5x to 4x magnification

## 🚀 Getting Started

### Option 1: Direct Use
Simply open `index.html` in any modern web browser.

### Option 2: Local Server
```bash
# Clone the repository
git clone https://github.com/yourusername/game-of-life.git

# Navigate to the directory
cd game-of-life

# Start a local server (Python 3)
python -m http.server 8000

# Or with Node.js
npx http-server

# Open in browser
# Navigate to http://localhost:8000
```

### Option 3: GitHub Pages
Fork this repository and enable GitHub Pages in your repository settings to host your own version.

## 📁 Project Structure

```
game-of-life/
│
├── index.html      # The complete game (HTML, CSS, and JavaScript)
├── README.md       # This file
└── LICENSE         # MIT License
```

## 🎨 Customization

Want to customize the game? Here are some ideas:

- **Change Colors**: Modify the `#00ff88` color value for cells
- **Adjust Grid Size**: Change `GRID_WIDTH` and `GRID_HEIGHT` constants
- **Add Patterns**: Add new patterns to the `patterns` object
- **Modify Rules**: Experiment with different cellular automaton rules

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Credits

Created by [Max Reddel](https://www.linkedin.com/in/maxreddel/) together with Claude, based on John Conway's original Game of Life (1970).

## 🌟 Acknowledgments

- **John Conway** - For creating this fascinating zero-player game
- **The Game of Life Community** - For discovering and documenting countless interesting patterns
- **Claude (Anthropic)** - For assistance in building this implementation

## 📚 Learn More

- [Conway's Game of Life - Wikipedia](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)
- [LifeWiki - The Game of Life Wiki](https://conwaylife.com/wiki/Main_Page)
- [Patterns Collection](https://conwaylife.com/wiki/Category:Patterns)
