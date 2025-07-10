# 🐍 Snake Game - Classic Arcade Fun

A modern take on the classic Snake game with customizable features, shop system, and user accounts. Built with HTML5 Canvas, CSS3, and vanilla JavaScript.

![Snake Game Preview](https://img.shields.io/badge/Game-Snake%20Game-green)
![Version](https://img.shields.io/badge/Version-1.0-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🎮 Live Demo

**Play the game online:** [Snake Game Demo](https://yourusername.github.io/snake-game)

## ✨ Features

### 🎯 Core Gameplay
- **Classic Snake mechanics** - Navigate, eat apples, grow longer
- **Progressive speed** - Game gets faster as you eat more apples
- **Collision detection** - Wall and self-collision handling
- **Score tracking** - Real-time score and high score system

### 🎨 Customization
- **5 Snake Costumes**: Green, Blue, Red, Purple, Gold
- **8 Wallpapers**: Forest, Ocean, Sunset, Night, Candy, Lava, Space, Default
- **Shop System** - Earn coins and unlock premium items
- **Real-time costume switching** - Change snake appearance instantly

### 👤 User System
- **Account creation** - Save progress across devices
- **Local storage** - Persistent high scores and purchases
- **Cross-device sync** - Play on any device with same account

### 🛒 Shop Features
- **Coin system** - Earn 5 coins per apple eaten
- **Premium costumes** - Rainbow, Neon, Fire, Ice snakes
- **Premium wallpapers** - Beautiful background themes
- **Purchase tracking** - Remember owned items

## 🚀 Quick Start

### Play Online
1. Visit the live demo: [Snake Game](https://yourusername.github.io/snake-game)
2. Click "Play Now" to start the game
3. Use arrow keys or WASD to control the snake
4. Eat apples to grow and earn coins!

### Local Development
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/snake-game.git
   cd snake-game
   ```

2. **Open in browser**
   - Open `index.html` for the main website
   - Open `snake.html` for direct game access

3. **Start playing!**
   - No installation required
   - Works in any modern browser

## 🎯 How to Play

### Basic Controls
- **Arrow Keys** or **WASD** - Control snake direction
- **Spacebar** - Pause/Resume game
- **Touch/Swipe** - Mobile controls supported

### Game Rules
1. **Start the game** by clicking "Start Game"
2. **Navigate** your snake using arrow keys or WASD
3. **Eat red apples** to grow longer and earn points
4. **Avoid collisions** with walls or your own tail
5. **Collect coins** (5 per apple) to spend in the shop
6. **Try to beat** your high score!

### Shop System
1. **Earn coins** by eating apples during gameplay
2. **Click "🛒 Shop"** to open the shop
3. **Browse costumes** and wallpapers
4. **Purchase items** with your earned coins
5. **Apply changes** instantly in-game

### User Accounts
1. **Click "👤 Login"** to create an account
2. **Register** with username and password
3. **Save progress** - coins, high scores, purchases
4. **Play anywhere** - progress syncs across devices

## 📁 Project Structure

```
snake-game/
├── index.html          # Main website landing page
├── snake.html          # Snake game page
├── snake.css           # Game styles
├── snake.js            # Game logic and mechanics
├── website.css         # Website styles
├── website.js          # Website interactions
└── README.md          # This file
```

## 🛠️ Technical Details

### Built With
- **HTML5** - Structure and Canvas API
- **CSS3** - Styling and animations
- **JavaScript (ES6+)** - Game logic and interactions
- **Local Storage** - Data persistence
- **Canvas API** - Game rendering

### Browser Support
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

### Performance
- **60 FPS** gameplay
- **Responsive design** for all screen sizes
- **Touch controls** for mobile devices
- **Optimized rendering** for smooth gameplay

## 🎨 Game Features

### Snake Costumes
| Costume | Price | Description |
|---------|-------|-------------|
| 🟢 Green | Free | Classic green snake |
| 🔵 Blue | Free | Cool blue variant |
| 🔴 Red | Free | Fiery red snake |
| 🟣 Purple | Free | Royal purple snake |
| 🟡 Gold | Free | Golden snake |
| 🌈 Rainbow | 50 coins | Colorful gradient snake |
| 💚 Neon | 75 coins | Glowing neon colors |
| 🔥 Fire | 100 coins | Hot fiery snake |
| ❄️ Ice | 100 coins | Cool frosty snake |

### Wallpapers
| Wallpaper | Price | Theme |
|-----------|-------|-------|
| Default | Free | Classic dark theme |
| 🌲 Forest | 30 coins | Natural green environment |
| 🌊 Ocean | 40 coins | Deep blue waters |
| 🌅 Sunset | 50 coins | Warm orange skies |
| 🌙 Night | 60 coins | Dark mysterious night |
| 🍭 Candy | 70 coins | Sweet pink paradise |
| 🌋 Lava | 80 coins | Hot molten environment |
| 🚀 Space | 100 coins | Cosmic star field |

## 🔧 Customization

### Adding New Costumes
1. Open `snake.js`
2. Find the `getSnakeColors()` function
3. Add new costume colors:
```javascript
newCostume: {
    head: '#color',
    body: '#color',
    bodyLight: '#color',
    bodyDark: '#color',
    outline: '#color',
    scales: '#color'
}
```

### Adding New Wallpapers
1. Open `snake.js`
2. Find the `getWallpaper()` function
3. Add new wallpaper:
```javascript
newWallpaper: {
    background: '#color',
    grid: '#color'
}
```

## 🚀 Deployment

### GitHub Pages (Recommended)
1. **Create repository** on GitHub
2. **Upload files** to repository
3. **Enable GitHub Pages** in settings
4. **Get URL**: `https://username.github.io/snake-game`

### Netlify
1. **Go to** [netlify.com](https://netlify.com)
2. **Drag and drop** project folder
3. **Get URL**: `https://random-name.netlify.app`

### Vercel
1. **Go to** [vercel.com](https://vercel.com)
2. **Import** project from GitHub
3. **Deploy** automatically

## 🤝 Contributing

1. **Fork** the repository
2. **Create** a feature branch
3. **Make** your changes
4. **Test** thoroughly
5. **Submit** a pull request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Classic Snake Game** - Inspiration from the original arcade game
- **HTML5 Canvas** - For smooth game rendering
- **CSS3 Animations** - For beautiful visual effects
- **Local Storage API** - For data persistence

## 📞 Support

- **Issues**: Report bugs on GitHub
- **Questions**: Open a discussion
- **Feature Requests**: Submit via issues

## 🎯 Roadmap

- [ ] **Multiplayer mode** - Play with friends
- [ ] **Power-ups** - Special abilities and items
- [ ] **Level system** - Different challenges and obstacles
- [ ] **Sound effects** - Audio feedback and music
- [ ] **Mobile app** - Native mobile application
- [ ] **Leaderboards** - Global high score tracking

---

**Made with ❤️ for gaming fun!**

*Enjoy playing Snake Game - the classic arcade experience reimagined for the modern web!* 
