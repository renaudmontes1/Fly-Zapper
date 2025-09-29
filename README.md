# 🪰 Fly Zapper! 💩

A fun and addictive Apple Watch game where you must zap flies before they reach their target!

## 🎮 About the Game

Fly Zapper is an entertaining Apple Watch game that challenges your reflexes and timing. Flies spawn at the top of the screen and move toward the poop at the bottom. Your mission is simple: **tap the flies before they reach their destination!**

### 🎯 Game Features

- **Simple Controls**: Just tap to zap flies
- **Progressive Difficulty**: Flies get faster as your score increases
- **Real-time Physics**: Flies move with realistic targeting behavior
- **Score Tracking**: Keep track of your highest scores
- **Smooth Animations**: Flies rotate based on their movement direction

## 📱 Platform

- **Apple Watch** (watchOS)
- Built with **SwiftUI**
- Created for Apple Watch Series compatibility

## 🎲 How to Play

1. **Launch** the app on your Apple Watch
2. **Tap "Start Game"** to begin
3. **Watch** as flies appear at the top of the screen
4. **Tap** on flies before they reach the poop at the bottom
5. **Survive** as long as possible - flies get faster with each successful zap!
6. **Game Over** when a fly reaches the poop

### 🏆 Scoring

- **+1 point** for each fly zapped
- **Speed increases** by 20 points per successful zap
- Try to beat your high score!

## 🛠️ Technical Details

### Architecture
- **SwiftUI** for the user interface
- **ObservableObject** pattern for game state management
- **Timer-based** animation system running at 60 FPS
- **Geometry calculations** for collision detection

### Key Components
- `GameState`: Manages game logic, fly movement, and scoring
- `ContentView`: Main game interface with welcome screen, game view, and about screen
- Real-time collision detection between flies and targets

## 📂 Project Structure

```
Fly Zapper/
├── Fly Zapper Watch App/
│   ├── ContentView.swift          # Main game logic and UI
│   ├── Fly_ZapperApp.swift       # App entry point
│   ├── Assets.xcassets/           # App icons and assets
│   └── Preview Content/
├── Fly Zapper Watch AppTests/     # Unit tests
├── Fly Zapper Watch AppUITests/   # UI tests
└── Fly Zapper.xcodeproj/         # Xcode project files
```

## 🚀 Getting Started

### Prerequisites
- Xcode 14.0 or later
- Apple Watch (for testing on device)
- watchOS 9.0 or later

### Installation
1. Clone this repository
2. Open `Fly Zapper.xcodeproj` in Xcode
3. Select your Apple Watch as the target device
4. Build and run the project

### Development Setup
```bash
# Clone the repository
git clone https://github.com/renaudmontes1/Fly-Zapper.git
cd Fly-Zapper

# Open in Xcode
open "Fly Zapper.xcodeproj"
```

## 🎨 Game States

The game includes multiple states:
- **Welcome Screen**: Game introduction with start button
- **Playing**: Active gameplay with fly zapping action
- **Game Over**: Score display with restart option
- **About**: Information about the developer

## 🔧 Customization

You can easily modify the game by adjusting these parameters in `ContentView.swift`:

- **Initial Speed**: Change `flySpeed = 100.0`
- **Speed Increase**: Modify `flySpeed += 20`
- **Collision Distance**: Adjust collision detection radius
- **Fly Size**: Change the emoji font size
- **Game Colors**: Modify the color scheme

## 🏢 Developer

**Created by PooPooGames**  
Website: [www.poopoogames.com](http://www.poopoogames.com)

## 📄 License

This project was created by Renaud Montes on September 18, 2025.

## 🤝 Contributing

Feel free to contribute to this project by:
- Reporting bugs
- Suggesting new features
- Submitting pull requests
- Improving documentation

## 🎯 Future Enhancements

Potential improvements for future versions:
- Multiple fly types with different behaviors
- Power-ups and special abilities
- High score persistence
- Sound effects and haptic feedback
- Multiplayer challenges
- Different game modes

---

**Enjoy zapping flies!** 🪰⚡️

*Don't let them reach the poop!* 💩