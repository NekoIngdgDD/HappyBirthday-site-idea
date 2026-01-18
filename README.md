# 🎉 Happy Birthday Pingu - Interactive Birthday Celebration Website

A beautiful, interactive HTML/CSS/JavaScript web application dedicated to celebrating Pingu's birthday with gifts, memories, timeline, wishes, and special messages.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Pages Guide](#pages-guide)
- [Customization](#customization)
- [Technologies Used](#technologies-used)
- [Browser Support](#browser-support)

---

## 📖 Overview

This is a special birthday celebration website designed as an interactive experience for Pingu. The site features multiple pages with animations, interactive elements, and multimedia content (images, videos, and music) to create a memorable birthday celebration.

Perfect for:
- Birthday celebrations
- Special occasions
- Memory sharing
- Gift exchanges
- Creating memorable digital experiences

---

## ✨ Features

### 🎨 Visual Effects
- **Snow/Celebration Animation** - Falling snowflakes and emojis (cake, gifts, balloons)
- **Smooth Animations** - Floating balloons, pulsing effects, and transitions
- **Glassmorphism Design** - Modern glass container effects with transparency
- **Interactive Cards** - Flipping cards with hover effects
- **Sparkle Overlays** - Decorative sparkles on card images

### 🌙 User Experience
- **Dark/Light Theme Toggle** - Switch between light and dark modes
- **Background Music Control** - Play/pause background music with audio toggle
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **Loading Animation** - Preloader with penguin emoji and loading text
- **Smooth Navigation** - Easy navigation between pages with previous/next buttons

### 📱 Interactive Elements
- **Navigation Badges** - Display current page status
- **Quick Navigation Buttons** - Fast access to different sections
- **Clickable Cards** - Navigate to different pages by clicking cards
- **Confetti Effects** - Canvas confetti animations on certain pages

### 🎵 Multimedia Support
- **Background Music** - Different tracks for different pages
- **Image Assets** - Penguin and character images
- **Memory Videos** - Video support in memories section
- **Image Galleries** - Organized image directories

---

## 📁 Project Structure

```
HappyBirthdayPingu/
│
├── index.html              # Homepage - Main entry point
├── biu.html               # Biu page (first page after home)
├── timeline.html          # Timeline of memories
├── gifts.html             # Gifts section
├── message.html           # Messages/wishes
├── memories.html          # Photo/video memories
├── wish.html              # Birthday wishes
├── manga.html             # Manga/comic section
│
├── index.css              # Homepage styles
├── biu.css               # Biu page styles
├── timeline.css          # Timeline styles
├── gifts.css             # Gifts section styles
├── message.css           # Messages page styles
├── memories.css          # Memories page styles
├── wish.css              # Wishes page styles
├── manga.css             # Manga page styles
├── styles.css            # Global/shared styles
│
├── love.js               # Special effects and animations script
├── package.json          # Project dependencies and metadata
├── README.md             # This file
│
└── assets/
    ├── images/           # General images (pingu.png, neko.png, etc.)
    ├── memoriesimage/    # Photo memories
    ├── memoriesvideo/    # Video memories
    └── songs/            # Background music files
        ├── NewJeans 'New Jeans...' (used on home page)
        └── yg cham shig.mp3 (used on timeline)
```

---

## 🚀 Installation

### Prerequisites
- Node.js and npm installed on your system
- A modern web browser (Chrome, Firefox, Safari, Edge)

### Setup Steps

1. **Clone/Download the Project**
   ```bash
   cd HappyBirthdayPingu
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```
   This will install the `serve` package for local development.

3. **Start the Development Server**
   ```bash
   npm start
   ```
   The website will open at `http://localhost:3000` (or next available port)

4. **Open in Browser**
   - The application should automatically open in your default browser
   - If not, manually navigate to `http://localhost:3000`

### Alternative (No Setup Required)
You can simply open `index.html` directly in your browser:
- Double-click `index.html` to open it locally
- No server or installation needed for basic functionality

---

## 📖 How to Use

### 1. **Homepage (index.html)**
   - Click the main card to navigate to the "Biu" page
   - Use quick navigation buttons to jump to other sections
   - Toggle theme with the 🌙 button (top-right)
   - Toggle music with the 🔈 button
   - Watch falling snowflakes and celebration emojis

### 2. **Navigation**
   - Use **Previous (⬅️)** and **Next (➡️)** buttons to navigate between pages
   - Each page has its own unique theme and content
   - Main navigation flow: Home → Biu → Timeline → Gifts → Message → Memories → Wish → Manga

### 3. **Interactive Features**
   - **Theme Toggle**: Switch between dark and light modes on any page
   - **Music Control**: Control background music playback
   - **Hover Effects**: Cards and buttons have interactive hover animations
   - **Confetti**: Triggered on special pages for celebratory effects

### 4. **Content Sections**
   - **Timeline**: Chronological journey of memories
   - **Gifts**: Special gifts section with animations
   - **Messages**: Birthday messages and wishes
   - **Memories**: Photo and video galleries
   - **Wishes**: Birthday wishes collection

---

## 📄 Pages Guide

### 🏠 **index.html** - Homepage
- Welcome message "Welcome, Pingu! 💖"
- Flipping card with Pingu/Neko images
- Quick navigation to all main sections
- Falling snowflakes and celebration emojis
- Background music (New Jeans track)

### 🌟 **biu.html** - Biu Page
- First page after home
- "Collecting this wasn't easy — your star is my motivation to keep going!"
- Contributions welcome
- Pulsing badge animation
- Custom styling with gradient backgrounds

### ⏰ **timeline.html** - Timeline
- Chronological journey through memories
- Important dates and milestones
- Visual timeline representation
- Background music (yg cham shig.mp3)
- Navigation between pages

### 🎁 **gifts.html** - Gifts
- Gift showcase section
- Floating balloon animations
- Confetti effects on interaction
- Gift cards with styling

### 💌 **message.html** - Messages
- Birthday messages section
- Display of special messages
- Unique styling and animations

### 📸 **memories.html** - Memories
- Photo gallery from `memoriesimage/` folder
- Video gallery from `memoriesvideo/` folder
- Image and video viewing
- Memory collection display

### 🎊 **wish.html** - Wishes
- Birthday wishes collection
- Wish display and showcase
- Celebratory styling

### 📚 **manga.html** - Manga
- Comic/manga section
- Unique visual presentation
- Custom styling

---

## 🎨 Customization

### Changing Images
1. Replace images in the `assets/images/` folder
2. Update HTML file references:
   - `pingu.png` - Main Pingu character
   - `neko.png` - Secondary character
   - `Penguin.png` - Favicon
   - `favicon.ico` - Browser favicon

### Adding Memories
1. Add photos to `assets/memoriesimage/` folder
2. Add videos to `assets/memoriesvideo/` folder
3. Reference them in `memories.html`

### Changing Background Music
1. Add new audio files to `assets/songs/` folder
2. Update the `<audio>` source in HTML files:
   ```html
   <source src="assets/songs/your-song.mp3" type="audio/mp3">
   ```

### Customizing Text
1. Open any `.html` file in a text editor
2. Find and replace text content
3. Save the file

### Modifying Colors
1. Edit the corresponding `.css` file
2. Look for color properties (hex codes, gradients)
3. Example: `background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);`
4. Save changes and refresh browser

### Adding New Pages
1. Create a new HTML file (e.g., `newpage.html`)
2. Copy structure from an existing page
3. Link it in navigation buttons
4. Create corresponding CSS file if needed

---

## 🛠️ Technologies Used

### Frontend Stack
- **HTML5** - Semantic markup and structure
- **CSS3** - Advanced styling, animations, and responsive design
- **JavaScript** - Interactive features and DOM manipulation

### External Libraries
- **Google Fonts** - Quicksand and Comfortaa font families
- **Canvas Confetti** - Confetti animation effects (cdn.jsdelivr.net)

### Key CSS Features
- CSS Animations (keyframes)
- CSS Grid and Flexbox
- Linear and Radial Gradients
- Transform and Transition effects
- Media Queries for responsiveness

### JavaScript Functions
- `toggleTheme()` - Switch dark/light theme
- `toggleMusic()` - Play/pause background music
- `navigateTo()` - Navigate between pages
- Theme persistence using localStorage

---

## 🌐 Browser Support

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full Support |
| Firefox | ✅ Full Support |
| Safari  | ✅ Full Support |
| Edge    | ✅ Full Support |
| Opera   | ✅ Full Support |
| IE 11   | ⚠️ Limited Support |

**Note**: For best experience, use modern browsers (Chrome, Firefox, Safari, or Edge)

---

## 📦 Project Dependencies

```json
{
  "devDependencies": {
    "serve": "11.2.0"
  }
}
```

**serve** - A simple HTTP server for local development

---

## 🎯 Tips & Tricks

1. **Preloader Animation** - The loading animation shows on page load. Customize it by editing the preloader div in HTML.

2. **Snow Effect** - Change snowflake symbols in `index.html` by replacing the emoji characters in the snowflake divs.

3. **Dark Mode** - The theme toggle uses localStorage to persist user preference across sessions.

4. **Audio Control** - Different pages can have different background tracks. Customize the `<audio>` src attribute.

5. **Responsive Design** - The site uses CSS media queries. Adjust breakpoints in the CSS files for different screen sizes.

6. **Animation Speed** - Modify animation `duration` and `delay` in CSS to adjust animation speeds.

---

## 📝 License

This project is distributed under the **MIT License**. Feel free to use, modify, and distribute as needed.

---

## 👨‍💻 Author

Original Template by: Ives van Hoorne

---

## 🎉 Enjoy the Celebration!

This is a special website designed to celebrate Pingu's birthday. Feel free to customize it and make it even more special!

**Happy Birthday, Pingu! 🎊🎁🎈**

---

## ❓ Troubleshooting

### Music not playing?
- Check if audio files exist in `assets/songs/` folder
- Ensure browser allows audio autoplay
- Check browser console for errors

### Images not loading?
- Verify image files exist in correct folders
- Check file paths in HTML (case-sensitive on some systems)
- Ensure correct file extensions (.png, .jpg, etc.)

### Styles not applying?
- Clear browser cache (Ctrl+Shift+Delete or Cmd+Shift+Delete)
- Check if CSS files are linked correctly in HTML
- Verify file paths are correct

### Theme toggle not working?
- Check browser console for JavaScript errors
- Ensure JavaScript is enabled in browser
- Try clearing localStorage and refreshing

---

**For more help, check the HTML files and CSS files for comments and detailed structure!**
