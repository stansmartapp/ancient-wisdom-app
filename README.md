# 🔮 Ancient Wisdom - Spiritual Mobile App

A beautiful, mobile-first spiritual fortune telling app that provides personalized personality readings based on user information and photos.

![Ancient Wisdom App](https://via.placeholder.com/800x400/8B0000/FFFFFF?text=Ancient+Wisdom+App)

## ✨ Features

- **🎬 Intro Video Experience**: Smooth autoplay with spiritual branding
- **📱 Mobile-First Design**: Optimized for iOS and Android devices
- **📝 Single-Page Form**: Streamlined user experience with all fields on one page
- **📷 Photo Integration**: Camera capture + gallery upload with live preview
- **🎨 Vintage Typography**: Beautiful Cinzel font for authentic feel
- **🔴 Red & Gold Theme**: Consistent branding throughout
- **⚡ PWA Ready**: Installable as native app on mobile devices
- **🔮 Mystical Loading**: Beautiful crystal ball animation
- **📊 Personality Reading**: AI-powered spiritual insights

## 🚀 Live Demo

**Try it now**: [https://wzlmrynv.manus.space](https://wzlmrynv.manus.space)

## 📱 Mobile Experience

The app is designed mobile-first and provides:
- Touch-friendly interface with 48px minimum touch targets
- Smooth transitions and micro-interactions
- Progress indicators and visual feedback
- Responsive design that adapts to all screen sizes
- PWA capabilities for native app-like experience

## 🛠️ Tech Stack

- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Styling**: Custom CSS with Google Fonts (Cinzel)
- **Media**: Video background, image processing
- **PWA**: Service Worker, Web App Manifest
- **Deployment**: Static hosting compatible

## 📁 Project Structure

```
FortuneTellerAI/
├── index.html              # Main HTML file
├── src/
│   └── app.js              # Main application logic
├── assets/
│   ├── introvideo.mp4      # Intro video
│   └── appbackground.png   # Background image
├── manifest.json           # PWA manifest
├── sw.js                   # Service worker
└── README.md              # This file
```

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)

1. **Fork this repository**
2. **Go to Settings > Pages**
3. **Select "Deploy from a branch"**
4. **Choose "main" branch**
5. **Your app will be live at**: `https://yourusername.github.io/FortuneTellerAI`

### Option 2: Local Development

```bash
# Clone the repository
git clone https://github.com/yourusername/FortuneTellerAI.git

# Navigate to project directory
cd FortuneTellerAI

# Start a local server (Python)
python3 -m http.server 3000

# Or use Node.js
npx serve .

# Open browser to http://localhost:3000
```

### Option 3: Deploy to Netlify

1. **Connect your GitHub repo to Netlify**
2. **Build settings**: Leave empty (static site)
3. **Publish directory**: `/` (root)
4. **Deploy automatically on push**

### Option 4: Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `src/app.js`:

```css
/* Main brand colors */
color: #8B0000;  /* Dark red */
background: linear-gradient(135deg, #D4AF37 0%, #FFD700 100%);  /* Gold */
```

### Updating Fonts

Modify the Google Fonts import in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;500;600;700&display=swap" rel="stylesheet">
```

### Backend Integration

Replace the mock API call in `callPersonalityAPI()` function:

```javascript
async callPersonalityAPI() {
    const response = await fetch('YOUR_API_ENDPOINT', {
        method: 'POST',
        headers: {
            'Content-Type': 'application/json',
        },
        body: JSON.stringify(this.userData)
    });
    return response.json();
}
```

## 📱 PWA Installation

Users can install the app on their devices:

### iOS (Safari)
1. Open the app in Safari
2. Tap the Share button
3. Select "Add to Home Screen"

### Android (Chrome)
1. Open the app in Chrome
2. Tap "Add to Home Screen" banner
3. Confirm installation

## 🔧 Development

### File Structure

- `index.html` - Main HTML structure and meta tags
- `src/app.js` - All application logic and styling
- `manifest.json` - PWA configuration
- `sw.js` - Service worker for offline functionality

### Key Functions

- `loadIntroScreen()` - Displays video intro
- `showFormScreen()` - Single-page form
- `validateAllFields()` - Form validation
- `submitForm()` - Handles form submission
- `showLoadingScreen()` - Mystical loading animation
- `showResultScreen()` - Displays personality reading

## 🌟 Features in Detail

### Intro Screen
- Auto-playing background video
- Vintage "ANCIENT WISDOM" title in Cinzel font
- Golden CTA button with red text
- Responsive design for all devices

### Form Experience
- Single-page layout (no multi-step navigation)
- Real-time validation with helpful error messages
- Photo upload with camera/gallery options
- Touch-optimized inputs and buttons

### Loading Animation
- Beautiful crystal ball with mystical effects
- Smooth CSS animations
- Branded loading messages

### Results Display
- Formatted personality reading
- Action buttons (Share, Save, New Reading)
- Scrollable content with proper typography

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

If you have any questions or need help with deployment, please open an issue in this repository.

---

**Made with ❤️ for spiritual seekers everywhere**

🔮 *Discover the mysteries of your soul with Ancient Wisdom*

