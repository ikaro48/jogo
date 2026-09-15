# 🏭 Cidade Poluída

An interactive 3D environmental game built with **Three.js** where you navigate a polluted city and work to reduce pollution levels.

## 🎮 Game Overview

**Cidade Poluída** (Polluted City) is a WebGL-based game that demonstrates the visual and environmental impact of pollution. Navigate through a 3D urban environment, interact with pollution mechanics, and see how your cleanup efforts transform the world around you.

## 🕹️ Controls

| Control | Action |
|---------|--------|
| **W / A / S / D** | Move forward / left / backward / right |
| **Mouse Click + Drag** | Look around (pointer lock) |
| **L** | Clean (reduce pollution level) |

## 🎨 Features

- **Dynamic Pollution System**: Pollution level (0-100%) affects:
  - Sky color (clean blue → polluted brown)
  - Fog density and visibility
  - Ambient and directional lighting
  - Overall visual atmosphere

- **3D Graphics**: Built with Three.js for smooth WebGL rendering
- **Pointer Lock Controls**: Immersive first-person camera control
- **Real-time HUD**: Visual feedback showing current pollution level
- **Responsive Design**: Adapts to window resizing

## 📁 Project Structure

```
jogo/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Styles for UI elements
├── js/
│   └── game.js         # Game logic and Three.js scene setup
└── README.md           # This file
```

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/ikaro48/jogo.git
   cd jogo
   ```

2. Open `index.html` in a modern web browser (supports WebGL)

3. Use the controls above to play

## 🌍 How It Works

### Pollution Mechanics

The pollution system is controlled by a `pollution` variable (0.0 to 1.0):

- **Visual Effects**:
  - Fog density scales with pollution
  - Sky color transitions from clean blue to polluted brown
  - Lighting becomes warmer/darker as pollution increases

- **Cleanup**: Pressing **L** reduces the pollution level and improves the environment

### Scene Components

- **Camera**: First-person perspective starting at position (0, 5, 20)
- **Lighting**: 
  - Ambient light for overall illumination
  - Directional light from above with shadow mapping
- **Fog**: Exponential fog that responds to pollution levels
- **Controls**: PointerLockControls for intuitive navigation

## 🛠️ Technologies

- **Three.js 0.160.0**: 3D graphics and rendering
- **JavaScript (ES6 Modules)**: Game logic
- **WebGL**: GPU-accelerated graphics
- **HTML5**: Structure
- **CSS3**: Styling and animations

## 📝 Notes

- Requires a modern browser with WebGL support
- Best experienced with a mouse and keyboard
- The game demonstrates environmental awareness through interactive gameplay

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

## 📄 License

This project is open source. Feel free to use, modify, and distribute as needed.

---

Made with 🌱 for environmental awareness
