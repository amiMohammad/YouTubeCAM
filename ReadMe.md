# YouTubeCAM UserScript

A UserScript for searching for and playing YouTube music directly on `app.camkrolik.com.br`.

## 🚀 Quick Installation

### 1. Install a UserScript Manager
Choose one of the following options:
- **[Tampermonkey](https://www.tampermonkey.net/)** (Recommended — Chrome, Firefox, Edge, Safari)
- **[Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)** (Firefox)
- **Violentmonkey** (Chrome, Firefox, Edge)

### 2. Install the Script
1. Open your UserScript manager's dashboard.
2. Click "Create a new script."
3. Delete all the default content.
4. Paste the complete code from the `youtube.js` file.
5. Save the script (Ctrl+S).
6. The script will automatically activate on `app.camkrolik.com.br`.

## 📖 How to Use

### Step-by-Step Guide:
1. Visit `https://app.camkrolik.com.br/`.
2. Wait 3 seconds — a YouTube button will appear in the sidebar.
3. Click the button to open the side panel.
4. Enter what you want to search for (song, artist, etc.).
5. Select the type: Video, Playlist, or Live.
6. Click "Search" or press Enter.
7. Click any result to play it.

### Features:
- **Search:** Videos, playlists, and live streams.
- **Fixed player:** Plays content in the upper-right corner.
- **History:** Automatically saves watched videos.
- **Favorites:** Add items to your favorites.
- **Direct links:** Paste YouTube links.
- **Continuous audio:** Audio continues playing when the panel is closed.

## ⚙️ API Configuration

### YouTube API Key
The script uses the YouTube Data API v3. The current key is:
```
AIzaSyAcl9uhYqUJ2H1aU_CzF1fDXWA7A9fenrI
```

### If the Key Stops Working:
1. Visit [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project.
3. Enable the "YouTube Data API v3."
4. Create a new API key.
5. Replace `YOUTUBE_API_KEY` in the script.

## 🔧 Technical Features

### Storage:
- **History:** localStorage (maximum of 20 videos).
- **Favorites:** localStorage (unlimited).
- **Cache:** Thumbnails and searches (temporary).

### Compatibility:
- ✅ Chrome, Firefox, Edge, Safari
- ✅ Desktop and mobile
- ✅ Windows, Mac, Linux

## 🐛 Troubleshooting

### Script Doesn't Appear:
- Reload the page.
- Make sure the UserScript manager is enabled.
- Wait more than 3 seconds.

### Search Doesn't Work:
- Check your internet connection.
- The API key may have expired or stopped working.
- Try reloading the page.

### Player Doesn't Play:
- Check whether any ad blockers are enabled.
- Test in incognito mode.
- Check your browser settings.

## 📝 Notes

- History is saved per browser (it does not sync across devices).
- Favorites are saved locally.
- The script only works on `app.camkrolik.com.br`.
- No login or account is required.

## 🤝 Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Implement your improvements.
3. Test thoroughly.
4. Submit a Pull Request.

## 📄 License

This UserScript is provided "as is." You are free to use, modify, and distribute it. Attribution to the original author (Felipe Prado) is appreciated.

---

**Developed by Felipe Prado** | **Current version:** 2.0
