# 🍅 Pomodoro CLI

A lightweight Pomodoro timer for Linux written in Bash.

## Features

- 🍅 60-minute work sessions
- ☕ 10-minute break sessions
- ⏳ Live countdown
- 🔔 Desktop notifications
- 🗣 Voice announcements
- ⌨ Press **Enter** to begin the next session
- ❌ Press **Ctrl+C** anytime to quit

## Requirements

Ubuntu / Kubuntu:

```bash
sudo apt install libnotify-bin speech-dispatcher
```

## Installation

Clone the repository:

```bash
git clone https://github.com/mlshika/pomodoro-cli.git
cd pomodoro-cli
```

Make the script executable:

```bash
chmod +x pomodoro
```

(Optional) Install it system-wide:

```bash
sudo cp pomodoro /usr/local/bin/
```

or for the current user:

```bash
cp pomodoro ~/.local/bin/
```

## Usage

Start a work session:

```bash
pomodoro work
```

Start a break:

```bash
pomodoro break
```

## License

MIT
