# Keyway MIDI Piano

A lightweight browser-based MIDI piano built with WebAudioFont and JavaScript.

Keyway lets you:

- Play piano using an external MIDI keyboard (or mouse clicks)
- Hear high-quality GM soundfont audio
- See visual feedback of key presses
- Warm up soundfonts in advance to avoid playback delays

This project is part of a larger goal to develop a better, more intuitive way to learn piano and music theory—one that’s free, fun, and fast.

## 🚀 Features

- 🎹 Two-octave interactive keyboard (C4–B5)
- 🔌 Real-time MIDI input support via Web MIDI API
- 🧠 Preloads soundfont samples to minimize latency
- 💡 Visual highlights on note trigger (via MIDI or click)
- 🧰 Designed for extensibility (staff rendering, lessons, etc.)

## 🛠 Tech Stack

- HTML5 / CSS3 / JavaScript
- [WebAudioFont](https://github.com/surikov/webaudiofont) for sound synthesis
- Web MIDI API for hardware input

## 🧪 Future Plans

- 🎵 Display played notes on musical staff
- 📊 Add note name labels and practice tracking
- 📱 Mobile/touch support
- 💬 Voice or chatbot-based feedback system
- 🔗 Integration with GitHub Pages for easy hosting

## 📂 File Structure

keyway/
├── index.html # Main entry point
├── css/
│ └── style.css # Styling
├── js/
│ ├── app.js # App logic
│ └── soundfont-loader.js # Optional: isolate WebAudioFont setup
├── assets/ # Media & extras
├── README.md
└── .gitignore


## 📄 License

MIT or GPL3 depending on final dependencies. (Currently using GPL3-licensed WebAudioFont.)

---

Pull requests welcome. Feedback even more welcome.
