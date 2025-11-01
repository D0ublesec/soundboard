# 🎲 Harmonomancer

A powerful, web-based soundboard designed for tabletop RPG sessions and immersive gaming experiences. Create atmospheric scenes, manage sound effects, and enhance your storytelling with this feature-rich audio companion.

![Harmonomancer Screenshot](https://via.placeholder.com/800x400/1e293b/a855f7?text=Harmonomancer+Soundboard)

## ✨ Features

### 🎵 Comprehensive Sound Library
- **20+ Categories** including Tavern & Inn, Combat & Battle, Magic & Spells, Horror & Suspense, and more
- **200+ High-Quality Sounds** covering every gaming scenario
- **Smart Tagging System** for easy discovery (ambient, event, loop, subtle, creature)

### 🎭 Scene Management
- **Custom Scenes** - Group multiple sounds that play together with preset volumes and delays
- **Default Scene Library** - Pre-built atmospheric scenes for quick setup
- **Advanced Timing** - Set individual sound delays (0-30 seconds) for staggered playback
- **Scene Looping** - Continuously replay scenes with smart loop handling

### ⭐ Favorites & Sessions
- **Game Sessions** - Separate sound collections for different campaigns
- **Favorites System** - Star sounds for quick access
- **Import/Export** - Share your setups with other DMs
- **Session Management** - Create, rename, and organize multiple game sessions

### 🎛️ Advanced Audio Controls
- **Individual Volume Control** - Remember volume settings per sound
- **Smart Mix Priority** - Automatically duck background sounds when priority sounds play
- **Loop Controls** - Set sounds to loop individually
- **Real-time Playback** - Play/pause/stop with visual feedback

### 🎯 User Experience
- **Quick Search** - Find sounds instantly by name, category, or tags
- **Keyboard Shortcuts** - Efficient controls for power users
- **Mobile Responsive** - Works perfectly on tablets and phones
- **Light/Dark Mode** - Choose your preferred theme
- **Active Sounds Bar** - Manage all playing sounds from one place

### 🎲 Gaming Tools
- **Dice Roller** - Roll d4, d6, d8, d10, d12, d20, d100 with animations
- **Coin Flipper** - Animated coin flips for quick decisions
- **Preset Collections** - Curated sound sets for specific games (Gloomhaven, Everdell, etc.)

## 🚀 Getting Started

### Quick Start
1. Download or clone this repository
2. Open `soundboard.html` in any modern web browser
3. Start playing sounds and creating your perfect gaming atmosphere!

### Adding Your Own Sounds
1. Create folders in the `/sounds/` directory for your categories
2. Add your audio files (supports .wav, .mp3, .flac)
3. Edit the `soundLibrary` object in the HTML file to include your new sounds:

```javascript
'Your Category': [
    { id: 'your-sound-id', name: 'Your Sound Name', url: '/sounds/your-category/your-file.wav', icon: '🎵' }
]
```

## 🎮 Perfect For

- **D&D Campaigns** - Enhance your dungeons with atmospheric sounds
- **Board Game Nights** - Add immersion to Gloomhaven, Everdell, and more
- **Horror Games** - Create spine-chilling atmospheres
- **Sci-Fi Adventures** - Spaceship hums, laser battles, and alien worlds
- **Fantasy Taverns** - Bustling crowds, crackling fires, and bardic music
- **Any Tabletop RPG** - Universal sound categories for every genre

## 📱 Keyboard Shortcuts

- **Space** - Play/pause all active sounds
- **S** - Stop all sounds
- **/** - Open search
- **1-9** - Play favorite sounds 1-9
- **Escape** - Close any modal

## 🛠️ Technical Features

- **Web Audio API** - High-quality audio with iOS compatibility
- **Local Storage** - All settings saved in your browser
- **No Server Required** - Runs entirely in your browser
- **Progressive Enhancement** - Works on all modern devices
- **Responsive Design** - Optimized for desktop, tablet, and mobile

## 📁 File Structure

```
harmonomancer/
├── soundboard.html          # Main application file
├── sounds/                  # Audio files directory
│   ├── tavern/             # Tavern & inn sounds
│   ├── combat/             # Battle and combat sounds
│   ├── magic/              # Spell and magic sounds
│   ├── horror/             # Horror and suspense sounds
│   └── ...                 # Additional categories
└── README.md               # This file
```

## 🎵 Sound Categories

- 🍺 **Tavern & Inn** - Crowds, music, fireplace, ale pouring
- ⚔️ **Combat & Battle** - Sword clashes, battle cries, war drums
- ✨ **Magic & Spells** - Fireballs, healing, teleportation, enchantments
- 🏰 **Dungeon & Cave** - Dripping water, chains, torch flames, traps
- 🌲 **Forest & Nature** - Birds, streams, wind, wildlife
- 🐉 **Creatures & Monsters** - Dragons, zombies, goblins, ghosts
- 🌧️ **Weather & Elements** - Rain, thunder, wind, storms
- 🏛️ **City & Town** - Markets, bells, blacksmiths, crowds
- 🌊 **Ocean & Sea** - Waves, ships, underwater, storms
- 💰 **Items & Objects** - Coins, chests, potions, books
- 🚪 **Doors & Movement** - Footsteps, creaking, opening doors
- 😱 **Horror & Suspense** - Heartbeats, whispers, screams, music boxes
- 🚀 **Sci-Fi & Futuristic** - Lasers, spaceships, robots, alarms
- 🏆 **Victory & Defeat** - Fanfares, achievements, celebrations
- And many more!

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

- **Add New Sounds** - Contribute high-quality audio files
- **Improve Categories** - Suggest new sound categories
- **Bug Reports** - Report issues or suggest improvements
- **Feature Requests** - Propose new functionality
- **Documentation** - Help improve this README

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 💖 Support

If you find Harmonomancer useful for your gaming sessions, consider:

- ⭐ **Starring this repository**
- 🐛 **Reporting bugs or suggesting features**
- 🎵 **Contributing new sounds or categories**
- ☕ **[Buying me a coffee](https://buymeacoffee.com/liamdouble)**

**Created by Liam Double** | [Buy me a coffee ☕](https://buymeacoffee.com/liamdouble)

*Enhance your tabletop adventures with the power of sound!*
