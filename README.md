# MASA Sonic Media Player

Audio playback engine and playlist workspace supporting audio formats with seek controls

## Technical Architecture

The application is architected with modular separation of concerns adhering to modern clean code standards:

- **Component Layering**: Isolated view layouts, state managers, and service controllers.
- **Defensive Engineering**: Robust input sanitization and exception management.
- **Modern Design Standards**: High-contrast dark-mode interface styled for optimal usability and visual polish.

## Preview

![Application Interface](screenshots/app_interface.png)

## Features

- Audio decoding pipeline supporting MP3 and WAV playback via Pygame mixer.
- Dynamic playlist loading, song queues, and metadata inspection.
- Transport controls: Play, Pause, Unpause, Stop, Next, and Previous track.
- Volume attenuation slider and track progression indicators.

## Prerequisites

- Python 3.10 or higher
- Required packages:

```bash
pip install customtkinter pillow requests
```

## Execution

Launch the application via Python:

```bash
python "Music Player App using Tkinter in Python/index.pyw"
```

## Project Structure

```
.
├── Music Player App using Tkinter in Python
├── screenshots/
│   └── app_interface.png
├── .gitignore
├── LICENSE             # MIT License
└── README.md           # Developer documentation
```

## License

This project is licensed under the terms of the MIT License. Refer to the `LICENSE` file for details.
