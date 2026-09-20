# Jarvis

Jarvis is a Windows desktop voice assistant with a futuristic PyQt interface, Gemini Live voice conversations, computer controls, persistent memory, and an optional phone dashboard.

## Features

- Real-time voice conversation with Gemini Live
- Keyboard and typed command input
- Persistent user memory and session summaries
- Application, browser, file, desktop, reminder, weather, flight, and game-update tools
- Screen and webcam analysis when requested
- Hardware telemetry for CPU, memory, GPU, and temperature where supported
- Custom assistant name, user name, voice, mode, theme, and audio devices
- Floating animated avatar and reactive HUD
- Optional encrypted local-network dashboard for phone control

## Requirements

- Windows 10 or Windows 11, 64-bit
- A working microphone and speaker for voice features
- Internet access
- A Google Gemini API key
- Permissions required by the Windows features you choose to use

Jarvis does not require Python, VS Code, pip, or other development tools.

## Installation

1. Open the latest Windows release in the [Releases](https://github.com/najimnajim75599-hub/application-jarvis/releases) section.
2. Download `Jarvis-Windows-x64-v1.0.0.zip`.
3. Extract the ZIP to a folder you can write to, such as `Downloads` or `Documents`.
4. Run `Jarvis.exe`.
5. Enter your Gemini API key when Jarvis asks for it.

Keep the extracted folder together. Jarvis stores its local settings, memory, and dashboard certificates beside the application so they persist between launches.

## Usage

Start `Jarvis.exe`, allow microphone access if Windows asks, and speak naturally. You can also type commands in the desktop interface. Use the settings controls to select audio devices, change the assistant voice, customize the interface, and enable or disable optional features.

The Remote Control feature displays a temporary pairing key or QR code for a phone on the same local network. The dashboard is optional and does not affect normal desktop use.

## Download

Download the latest tested Windows package from:

<https://github.com/najimnajim75599-hub/application-jarvis/releases/latest>

## Privacy and Security

Jarvis requires a Gemini API key to use Gemini services. The key is entered by the user and stored in the local application configuration; it is not included in this repository or release package. Conversations sent to Gemini are subject to Google's service terms and privacy policy.

Local memory, uploaded files, dashboard certificates, and runtime settings remain on the user's computer. Do not share the application data folder if it contains personal information or credentials.

Some commands can control the computer, change files, send messages, schedule tasks, or perform power actions. Review confirmations shown by Jarvis before allowing irreversible actions.

## License

See [LICENSE](LICENSE).

## Version

Current release: `v1.0.0`
