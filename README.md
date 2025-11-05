# 🎈 Balloon Math Burst

An interactive browser-based math game where players click balloons in ascending order based on arithmetic expressions. Test your mental math skills across 30 progressively challenging levels!

![Game Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🎮 Game Features

- **30 Progressive Levels**: From easy to extremely challenging
- **Random Expressions**: Every game generates unique arithmetic problems (+, −, ×, ÷)
- **Smart Difficulty Scaling**: 
  - Levels 1-10: Simple numbers with helpful feedback
  - Levels 11-30: Larger numbers with closer values, no wrong feedback (hardcore mode!)
- **Visual Feedback**: Beautiful burst animations and color-coded balloons
- **Sound Effects**: Web Audio API for pop sounds and feedback
- **Score Tracking**: Points system with time bonuses
- **Accuracy Metrics**: Track your performance
- **High Score**: Saved locally using localStorage
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## 🎯 How to Play

1. **Objective**: Click the balloons in ascending order (smallest to largest value)
2. **Calculate**: Solve the arithmetic expressions shown on each balloon
3. **Click**: Select the balloon with the smallest value first
4. **Continue**: Then click middle value, then largest value
5. **Beat the Timer**: Complete all 3 balloons within 10 seconds
6. **Progress**: Advance through 30 levels of increasing difficulty

### Difficulty Progression

| Levels | Difficulty | Number Range | Feedback |
|--------|------------|--------------|----------|
| 1-5    | Easy       | 5-25         | ✅ Shows wrong clicks |
| 6-10   | Medium     | 10-40        | ✅ Shows wrong clicks |
| 11-15  | Medium-Hard| 20-70        | ❌ Silent mode |
| 16-20  | Hard       | 30-100       | ❌ Silent mode |
| 21-30  | Expert     | 40-140       | ❌ Silent mode + Close values |

## 🚀 Getting Started

### Play Online
Simply open the game in any modern web browser:
```
https://rupesh8969.github.io/Bubble_game/balloon-game.html
```

### Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/rupesh8969/Bubble_game.git
   ```

2. Navigate to the directory:
   ```bash
   cd Bubble_game
   ```

3. Open the HTML file in your browser:
   ```bash
   # Windows
   start balloon-game.html
   
   # macOS
   open balloon-game.html
   
   # Linux
   xdg-open balloon-game.html
   ```

## 💻 Technical Details

- **Pure Vanilla JavaScript**: No frameworks or libraries required
- **Single File**: Everything in one HTML file (HTML + CSS + JS)
- **Web Audio API**: For sound effects without external audio files
- **CSS Animations**: Smooth floating balloon animations
- **LocalStorage**: High score persistence
- **Mobile-Friendly**: Touch and click support

## 🎨 Game Mechanics

### Scoring System
- **Base Points**: 100 points per level completion
- **Time Bonus**: +2 points per remaining second
- **Accuracy Tracking**: Percentage of correct clicks

### Special Features
- **No Duplicate Expressions**: Each round has unique problems
- **Value Clustering**: Higher levels generate expressions with closer results
- **Silent Mode**: After level 10, wrong clicks don't show feedback (increases difficulty)

## 📱 Browser Compatibility

- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera
- ✅ Mobile Browsers (iOS/Android)

## 🛠️ Technologies Used

- HTML5
- CSS3 (Animations, Gradients, Flexbox)
- Vanilla JavaScript (ES6+)
- Web Audio API

## 📸 Screenshots

### Game Interface
- Colorful floating balloons with arithmetic expressions
- Real-time score and timer display
- Smooth burst animations
- Professional result screen with statistics

## 🎯 Learning Outcomes

This game helps improve:
- ✅ Mental arithmetic skills
- ✅ Quick decision making
- ✅ Pattern recognition
- ✅ Time management under pressure
- ✅ Mathematical confidence

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Future Enhancements

- [ ] Leaderboard with online ranking
- [ ] Multiple difficulty modes
- [ ] Custom time limits
- [ ] More operations (exponents, square roots)
- [ ] Multiplayer mode
- [ ] Background music toggle
- [ ] Theme customization

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Developer

**Rupesh Kumar (VTU22264)**

- GitHub: [@rupesh8969](https://github.com/rupesh8969)
- Project Link: [https://github.com/rupesh8969/Bubble_game](https://github.com/rupesh8969/Bubble_game)

## ⭐ Show Your Support

Give a ⭐️ if you enjoyed playing this game!

---

<p align="center">
  Made with ❤️ by Rupesh Kumar | © 2025 All Rights Reserved
</p>
