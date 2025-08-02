MELODYMAP!
🎹 Keyboard Piano in Python (Pygame)
This is a virtual piano built using Pygame that lets you:
•	Play notes with your keyboard
•	See a heatmap of frequently used keys
•	Record and playback your performances
•	Change octaves and simulate a sustain pedal
________________________________________
🚀 Features
•	✅ White & Black Keys
o	Uses keys A to K (white) and W, E, T, Y, U (black)
•	🎶 Sound Support
o	Loads .wav files from a /sounds folder (named like C4.wav, D#4.wav, etc.)
•	🔥 Keyboard Heatmap
o	Tracks how often each note is played
•	⏺️ Recording & Playback
o	Press R to start/stop recording
o	Press P to replay your performance

•	🕊️ Sustain Pedal Simulation
o	Hold Space for longer note fade-outs
•	💾 Heatmap Auto-Save
o	Saves play count as heatmap_data.json on exit
________________________________________
🧩 Controls
Key	Action
A–K	White piano keys
W, E, T...	Black piano keys
R	Toggle recording
P	Playback recorded notes
	
Space	Sustain pedal
Close window	Save and exit
________________________________________
📁 Folder Structure
project/
│
├── main.py                  
├── heatmap_data.json        
└── sounds/                  
    ├── C4.wav
    ├── C#4.wav
    ├── D4.wav
    └── ...
________________________________________
📦 Requirements
•	Python 3.x
•	pygame module
Install with:
pip install pygame
________________________________________
🎨 Optional Enhancements
•	Add title text or dynamic overlays
•	Display current octave on screen
•	Animate key press effects
•	Show popup notifications (e.g. “Recording started…”)
________________________________________
🙌 Credits
Created using Pygame. Audio samples can be downloaded from:
•	https://freesound.org
•	https://samplefocus.com
•	https://partnersinrhyme.com
________________________________________

