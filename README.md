# Working Record Player

A functional and interactive record player built with HTML, CSS, and JavaScript. This project features animated vinyl rotation, play/pause controls, and volume adjustment.

## Features

- **Play/Pause Functionality**: Click the button to start and stop the music
- **Animated Vinyl Record**: Visual spinning animation that syncs with playback
- **Volume Control**: Adjustable slider to control audio volume
- **Responsive Design**: Clean, user-friendly interface
- **Smooth Animations**: CSS transitions for record rotation and tonearm movement

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- HTML5 Audio API

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- A code editor (VS Code, Sublime Text, etc.)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/tbarnett42/Working-Record-Player.git
```

2. Navigate to the project directory:
```bash
cd Working-Record-Player
```

3. Add your audio file:
   - Place an MP3 file in your project folder (or create an `audio` folder)
   - Update the `src` attribute in the `<audio>` tag in `index.html`:
   ```html
   <audio loop class="my-song" src="path/to/your-audio-file.mp3" preload="auto"></audio>
   ```

4. Open `index.html` in your browser to view the project

## Usage

1. Click the play button to start the music
2. The vinyl record will begin spinning and the tonearm will move into play position
3. Adjust the volume using the slider at the bottom
4. Click the button again to pause

## Project Structure

```
working-record-player/
│
├── index.html          # Main HTML file
├── style.css           # Styling and animations
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── audio/              # Audio files folder (you'll need to create this)
    └── song.mp3        # Your audio file
```

## Key JavaScript Features

- Event listeners for play/pause toggle
- DOM manipulation for adding/removing CSS classes
- setTimeout for animation timing
- Volume control with range input
- Audio API methods (play, pause, volume)

## What I Learned

- Working with the HTML5 Audio API
- Implementing play/pause toggle functionality
- Synchronizing CSS animations with JavaScript events
- Handling user input with event listeners
- Managing application state

## Future Enhancements

- Add multiple song selection
- Display current time and duration
- Add a progress bar
- Include song information display
- Add keyboard controls
- Implement playlist functionality

## Author

**Ty**
- Aspiring Application Engineer
- Currently pursuing Master's in Information Technology
- GitHub: [@tbarnett42](https://github.com/tbarnett42)

## Acknowledgments

- Tutorial by [Coding Artist](https://www.youtube.com/@CodingArtist) - "Working Record Player | HTML, CSS & Javascript"
- Audio: "Happy Christmas Music" by VibeHorn from [Pixabay](https://pixabay.com)

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: Make sure to use royalty-free music for any public demonstrations of this project.
