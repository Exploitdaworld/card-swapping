# 🃏 Card Swapping - Interactive Anime Character Cards

An interactive card swapping application featuring popular anime characters with smooth drag/swipe animations. Built using only HTML, CSS, and vanilla JavaScript with `<div>` elements.

## ✨ Features

- **Smooth Drag & Swipe**: Interactive card swiping with touch and mouse support
- **Anime Characters**: Features characters from popular anime series including:
  - Tanjiro (Demon Slayer)
  - Jinwoo (Solo Leveling)
  - Power (Chainsaw Man)
  - Pikachu (Pokémon)
  - Sakura (Naruto)
  - And more!
- **Responsive Design**: Works on desktop and mobile devices
- **Visual Feedback**: 
  - RGB glowing animations
  - Like/Nope badges during swipe
  - Smooth card transitions
  - Stacked card effect
- **Pure HTML/CSS/JS**: No frameworks or dependencies required

## 🚀 Demo

Simply open `card-swipe v2.html` in your browser to start swiping cards!

## 🎮 How to Use

1. **Swipe Right**: Like a character card
2. **Swipe Left**: Dismiss a character card
3. **Quick Fling**: Fast swipe gestures for instant card movement
4. **Drag & Release**: Partial swipes will snap back to center

## 📁 Project Structure

```
card-swapping/
├── card-swipe v2.html     # Main application file
├── README.md              # Project documentation
└── assets/               # Character images
    ├── tanjiro in action.gif
    ├── jinwoo.gif
    ├── power.gif
    ├── pikachu.gif
    ├── haruka sakura.gif
    ├── yourichi.gif
    ├── tanjiro.png
    └── sakura.png
```

## 🛠️ Technical Implementation

### Key Technologies
- **HTML5**: Semantic structure using only `<div>` elements
- **CSS3**: 
  - CSS Grid and Flexbox for layout
  - CSS Variables for dynamic theming
  - CSS Transforms for smooth animations
  - CSS Keyframes for RGB glow effects
- **Vanilla JavaScript**:
  - Pointer Events API for cross-device interaction
  - Touch gesture recognition
  - Velocity-based fling detection
  - Dynamic DOM manipulation

### Features Highlights
- **Constraint-based Design**: Built exclusively with `<div>` elements
- **Touch-first Approach**: Optimized for mobile interactions
- **Performance Optimized**: Uses `transform3d` and `will-change` for GPU acceleration
- **Responsive Layout**: Adapts to different screen sizes

## 🎨 Customization

You can easily customize the application by:

1. **Adding New Characters**: 
   - Add new image files to the project
   - Update the HTML to include new card elements
   - Follow the existing card structure

2. **Styling Changes**:
   - Modify CSS variables in `:root` for global changes
   - Update card dimensions with `--card-w` and `--card-h`
   - Customize colors, animations, and effects

3. **Interaction Settings**:
   - Adjust `SWIPE_THRESHOLD` for swipe sensitivity
   - Modify `MAX_ROT` for rotation intensity
   - Change animation durations and easing functions

## 🌟 Live Demo

View the project live at: [https://github.com/Exploitdaworld/card-swapping](https://github.com/Exploitdaworld/card-swapping)

## 📱 Browser Support

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Feel free to:
- Add new anime characters
- Improve animations and effects
- Enhance mobile responsiveness
- Fix bugs or optimize performance

## 📄 License

This project is open source and available under the MIT License.

---

**Built with ❤️ for anime fans and web developers!**
