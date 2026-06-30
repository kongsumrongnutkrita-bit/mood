# MoodTune 🎧 - Spotify Mood Co-Pilot

MoodTune is a premium, interactive single-page React web application that serves as a Spotify mood co-pilot. It curates custom playlist suggestions, syncs bilingual lyrics, and generates custom album cover art dynamically based on your current emotional state.

## 🚀 Key Features

1. **Intelligent Mood Cards**: Choose from 8 beautifully designed mood states (Happy, Sad, Angry, Surprised, Fearful, Disgusted, Calm, Excited), each styled with dynamic, custom-glow glassmorphism.
2. **AI Live DJ**: Describe your exact emotional state or music request in natural language (e.g., *"chill acoustic Thai songs for a rainy Sunday"*), and the AI Co-Pilot will construct a custom playlist of 6 real-world hits.
3. **Bilingual Lyrics Sync**: Synchronized display showing Thai verses with adjacent English translations in a clean, scrollable interface.
4. **AI Album Cover Generator**: Automatically draws high-quality graphical album artwork using Google's Imagen model matching the theme and title of your active song.
5. **Interactive Music Controller**: Adjust track progress bars, play/pause states, and watch the vinyl record spin and pop out of the album sleeve in real time.
6. **Secure Settings Panel**: A local configurations modal to save your Google Gemini API Key in browser storage safely.

## 🛠️ Technology Stack
- **Framework**: React.js (v18)
- **Styling**: Tailwind CSS (v3) + Custom CSS variables and animations
- **Icons**: Custom inline React SVGs (lucide inspired)
- **APIs**:
  - **Gemini**: Generates custom playlists and bilingual lyrics.
  - **Imagen**: Generates dynamic cover art.

## 💻 How to Run Locally

Since the application is fully self-contained in a single page:
1. Clone or download this repository.
2. Double-click [index.html](index.html) to open it in your browser.
3. (Optional) Click the **Settings Gear** icon on the top right to configure your Gemini API key and activate the AI Live DJ.
