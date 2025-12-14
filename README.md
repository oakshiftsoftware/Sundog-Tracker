# Sundog Tracker

**An unofficial companion app for Young Suns**

---

## 📱 About

Sundog Tracker is a companion application for the Young Suns Xbox game that helps players manage their crafting projects. Build a queue of blueprints you want to craft, view all required resources with their locations, and track your collection progress.

## ✨ Features

### Blueprint Management
- **Browse Blueprints**: View all available blueprints organized by type (Intermediates & Equipment)
- **Build Queue**: Create and manage a queue of items you want to craft
- **Blueprint Details**: See detailed information for each blueprint including:
  - Required resources with quantities
  - Crafting medium (where to build it)
  - Nested intermediate requirements

### Resource Tracking
- **Collection Tracker**: Comprehensive view of all resources needed for your build queue
- **Real-time Calculations**: Automatically expands intermediate blueprints to show base resource requirements
- **Location Information**: Each resource displays where it can be found in the game
- **Progress Tracking**: Track collected resources with multiple input methods:
  - ➕ Increment/➖ Decrement buttons
  - ✏️ Direct value entry
  - ❌ Quick reset to zero

### Data Management
- **Cloud-Based Data**: Fetches up-to-date blueprints and resources from CDN
- **Offline Support**: Caches data locally for offline use
- **Persistent Storage**: Your build queue and collection progress are saved automatically

### User Experience
- **Dark Theme**: Purple and amber color scheme optimized for comfortable viewing
- **Responsive Design**: Portrait-oriented mobile interface
- **Smooth Navigation**: Intuitive screen transitions and back navigation
- **Material Design**: Built with KivyMD for modern Android UI/UX

## 🎯 Use Cases

- **Plan Your Builds**: Queue up multiple blueprints and see total resource requirements
- **Efficient Farming**: Know exactly which resources to collect and where to find them
- **Track Progress**: Check off resources as you collect them during gameplay
- **Avoid Mistakes**: See intermediate requirements expanded so you don't miss any components

## 📋 Requirements

- **Android**: API 21+ (Android 5.0 Lollipop or higher)
- **Permissions**: Internet access (for fetching blueprint/resource data)
- **Architectures**: arm64-v8a, armeabi-v7a

## 🔧 Technical Details

- Built with Python 3 + Kivy + KivyMD
- Network requests via `requests` library
- Local JSON caching for offline functionality
- Threaded data loading to prevent UI blocking

## ⚠️ Disclaimer

This application is **unofficial** and **fan-made**. It is not affiliated with, endorsed by, or associated with KO_OP (the developers of Young Suns). All game content, trademarks, and references are the property of their respective owners. This app is provided as-is without warranty of any kind.

## 🐛 Known Limitations

- Requires internet connection on first launch to download blueprint/resource data
- Resource data is fetched from a CDN and may require updates when game content changes

## 📥 Installation

1. Download the APK from the latest Release
2. Enable "Install from Unknown Sources" in your Android settings if needed
3. Install the APK
4. Launch Sundog Tracker and start building!

## 💡 Tips

- Start by adding blueprints to your build queue from the "+" menu
- Tap any blueprint in your queue to view detailed requirements
- Use the clipboard icon to access the Collection Tracker
- Swipe left/right or use back button for navigation
- Your progress is saved automatically

## 🙏 Credits

**Developed by**: Oakshift Software  
**Game by**: KO_OP

---

*Happy crafting, Sundog! 🌟*
