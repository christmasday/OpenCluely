<div align="center">

# 🧠 OpenCluely 

<!-- Development Banner -->
<p align="center">
  <img src="https://img.shields.io/badge/Status-Under%20Active%20Development-FFA500?style=for-the-badge&logo=github&logoColor=white" alt="Under Active Development" />
</p>
<p align="center" style="margin-top:-8px;">
  <em>Core is working; improvements are shipping daily.</em>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=35&duration=3000&pause=1000&color=2D9CDB&center=true&vCenter=true&width=600&lines=OpenCluely;Invisible+Interview+Assistant;Multi-Model+AI+Power;Stealth+Technology+Expert" alt="OpenCluely Typing Animation" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OpenCluely-AI%20Assistant-2D9CDB?style=for-the-badge&logo=robot&logoColor=white" alt="OpenCluely Badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Cross%20Platform-blue?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/Stealth-100%25%20Invisible-red?style=flat-square" alt="Stealth" />
  <img src="https://img.shields.io/badge/LLM-Gemini%20%7C%20OpenRouter%20%7C%20Groq%20%7C%20Ollama-orange?style=flat-square" alt="LLM Providers" />
  <img src="https://img.shields.io/badge/Speech-Local%20Whisper%20%7C%20Azure%20%7C%20Groq-blueviolet?style=flat-square" alt="Speech" />
</p>

---


**OpenCluely** is a revolutionary AI-powered desktop application that provides **invisible, real-time assistance** during technical interviews, coding challenges, and meetings.

## 🎬 Demo Video

https://github.com/user-attachments/assets/896a7140-1e85-405d-bfbe-e05c9f3a816b
</div>

## 🌟 Why OpenCluely?

<table>
<tr>
<td width="50%">

### 🥷 **100% Stealth Mode**
- **Invisible to Screen Sharing**: Zoom, Teams, Meet, Discord
- **Process Disguise**: Appears as normal system process (Terminal, Activity Monitor, Settings)
- **Click-Through Windows**: Transparent overlay technology
- **Draggable UI**: Move windows anywhere on screen
- **Zero Detection**: Bypasses all recording software

</td>
<td width="50%">

### 🚀 **Multi-Provider AI Intelligence**
- **Flexible AI Backends**: Google Gemini (`@google/genai`), OpenRouter, Groq, and 100% offline Local Ollama
- **Specialized Modes**: General Assistant, Coding (with strict language enforcement), and Meeting Listener
- **Direct Image Analysis**: Screenshots are analyzed natively (no OCR latency)
- **Fast Voice Input & TTS**: Local OpenAI Whisper, Azure Speech, Groq Whisper Large V3 STT, and Orpheus TTS
- **Context Memory**: Remembers conversation history across queries

</td>
</tr>
</table>

## 🖼️ Modern UI Features

### 📱 **Interactive Windows**
- **Floating Overlay Bar**: Compact command center with camera capture, mic toggle, skill/mode switcher, and language selector
- **Draggable Answer Window**: Move and resize AI response window anywhere
- **Close Button**: Clean × button to dismiss the answer window when needed
- **Auto-Hide Mic**: Microphone button automatically appears only when a speech provider is configured
- **Interactive Chat**: Full conversation window with markdown rendering, syntax highlighting, and audio responses

### 🎨 **Visual Design**
- **Glassmorphism**: Beautiful blur effects and sleek dark mode transparency
- **Adaptive Layout**: UI elements dynamically adapt based on active mode (e.g., language picker visible in Coding mode)
- **Smart Resizing**: Windows resize smoothly to fit content
- **Professional Look**: Mimics system applications for perfect stealth

---

## 🎯 Functional Overview

### 📋 **Core Components**

<table>
<tr>
<td width="33%">

#### 🖱️ **Main Overlay**
- Floating command bar
- Screenshot capture (`⌘⇧S` / `Ctrl+Shift+S`)
- Microphone toggle (`Alt+R`)
- Skill / Mode switcher (`⌘↑` / `⌘↓` or click)
- Language picker (in Coding mode)
- Real-time status indicator

</td>
<td width="33%">

#### 💬 **Interactive Chat**
- Real-time voice transcription
- AI conversation & history
- Markdown & code block formatting
- Session memory
- Listening & thinking animations
- Auto-scroll messages

</td>
<td width="33%">

#### 📊 **Answer Window**
- Draggable interface
- Close button (×)
- Split layout for code & explanations
- Syntax highlighting
- Copy-to-clipboard button
- Smart content sizing

</td>
</tr>
</table>

### 🎭 **Operating Modes**

1. **General Mode** (`general`): Versatile assistant tailored for conceptual discussions, behavioral questions, system design, and broad problem-solving.
2. **Coding Mode** (`coding`): Programming-focused mode enforcing optimal time/space complexity and outputting clean, runnable solutions in your chosen language (**C++**, **Python**, **Java**, **JavaScript**, or **C**).
3. **Meeting Mode** (`meeting`): Passive listener mode that monitors conversations, identifies questions, extracts key action items, and generates structured meeting summaries.

---
## ✅ Development Status & Features

### 🎯 **Completed Features**

- [x] **Multi-Provider LLM Support**:
  - **Google Gemini**: Powered by `@google/genai` with fallback model chains (`gemini-2.5-flash`, `gemini-2.0-flash`, `gemini-1.5-flash`) and dual-method racing.
  - **OpenRouter**: Access Claude 3.5 Sonnet, GPT-4o, DeepSeek, and free vision models (`openrouter/free`).
  - **Groq**: Ultra-low-latency text generation via `llama-3.3-70b-versatile`.
  - **Local Ollama**: 100% offline local inference (`llama3.2`, etc.) with custom host endpoint support and automatic model discovery.
- [x] **Modes & Skill System**: General, Coding (with multi-language targeting), and Meeting listener modes.
- [x] **Speech-to-Text (STT)**:
  - **Local Whisper**: Offline local transcription with automatic `.venv-whisper` management and in-app model downloader (`turbo`, `base`, etc.).
  - **Azure Speech Services**: Real-time streaming recognition with interim live results.
  - **Groq STT**: Fast cloud transcription powered by Whisper Large V3 Turbo.
- [x] **Text-to-Speech (TTS)**: Natural voice playback powered by Groq Orpheus TTS (`orpheus-tts-0.1-ayane`).
- [x] **Stealth Overlay**: Draggable command bar, click-through toggling, and native window binding.
- [x] **Direct Vision Analysis**: Native screenshot image understanding without OCR bottlenecks.
- [x] **Global Shortcuts**: Complete keyboard shortcuts for capture, speech, visibility, interaction, mode switching, and window positioning.
- [x] **Session Memory**: In-memory context retention across queries with shortcut memory clearing.
- [x] **Onboarding & Settings Wizard**: In-app provider configuration, API key management, Whisper model manager, and stealth process customization.
- [x] **Cross-Platform Installers**: Automated builds for macOS (Apple Silicon & Intel), Windows (Installer & Portable), and Linux (DEB & AppImage).

### 🚧 **Planned Features** *(In Development)*

- [ ] **Hidden during screen share** (auto‑hide all windows when screen sharing is detected)
- [ ] **Auto‑typer for code snippets** (simulate typing into editors/IDEs)
- [ ] **Export conversation history** (save sessions as markdown/PDF)
- [ ] **Additional Local STT backends** (faster-whisper / whisper.cpp bindings)

---

## ⚙️ Configuration & Providers

OpenCluely supports configuring providers through the **in-app Settings window** (`⌘,` / `Ctrl+,`) or by editing `.env` directly.

### 1. LLM Provider Options

Set `LLM_PROVIDER` to `gemini`, `openrouter`, `groq`, or `ollama`:

```bash
# --- Google Gemini ---
LLM_PROVIDER=gemini
GEMINI_API_KEY=your_gemini_api_key_here

# --- OpenRouter ---
LLM_PROVIDER=openrouter
OPENROUTER_API_KEY=your_openrouter_key_here
OPENROUTER_MODEL=openrouter/free

# --- Groq ---
LLM_PROVIDER=groq
GROQ_API_KEY=your_groq_key_here
GROQ_MODEL=llama-3.3-70b-versatile

# --- Local Ollama ---
LLM_PROVIDER=ollama
OLLAMA_HOST=http://localhost:11434
OLLAMA_MODEL=llama3.2
```

### 2. Speech & Voice Options (Optional)

Set `SPEECH_PROVIDER` to `whisper`, `azure`, or `groq`:

```bash
# --- Local Whisper (Offline) ---
SPEECH_PROVIDER=whisper
WHISPER_COMMAND=whisper
WHISPER_MODEL_DIR=.whisper-models
WHISPER_MODEL=turbo
WHISPER_LANGUAGE=en
WHISPER_SEGMENT_MS=4000

# --- Azure Speech Services ---
SPEECH_PROVIDER=azure
AZURE_SPEECH_KEY=your_azure_speech_key
AZURE_SPEECH_REGION=your_azure_region

# --- Groq STT & TTS ---
SPEECH_PROVIDER=groq
GROQ_API_KEY=your_groq_key_here
GROQ_STT_MODEL=whisper-large-v3-turbo
GROQ_TTS_MODEL=orpheus-tts-0.1-ayane
GROQ_TTS_VOICE=tara
GROQ_TTS_SPEED=1.0
```

> [!NOTE]
> Voice recognition is completely optional. If no speech provider is configured, the microphone button will automatically hide.

---

## 📦 Download Pre-Built Installers

Download pre-built binaries for your platform from the [**Releases page**](https://github.com/TechyCSR/OpenCluely/releases):

| Platform | File | Notes |
|---|---|---|
| **Windows** | `OpenCluely-Setup-*.exe` | NSIS installer; auto-creates Start Menu shortcut |
| **Windows** | `OpenCluely-*-portable.exe` | Portable, no install required |
| **macOS (Apple Silicon)** | `OpenCluely-*-arm64.dmg` | M1 / M2 / M3 / M4 Macs |
| **macOS (Intel)** | `OpenCluely-*-x64.dmg` | Intel Macs |
| **Linux (Debian/Ubuntu)** | `OpenCluely-*.deb` | Auto-pulls system deps (Python 3.10+, ffmpeg, GTK, NSS) |
| **Linux (Universal)** | `OpenCluely-*.AppImage` | Portable executable (`chmod +x` then run) |

---

## 🚀 Quick Start & Installation

### ⚡ Three Simple Steps

1. **Clone the repository** (skip if you downloaded a pre-built installer):
   ```bash
   git clone https://github.com/TechyCSR/OpenCluely.git
   cd OpenCluely
   ```

2. **Run the setup script**:
   ```bash
   ./setup.sh
   ```

   The setup script will:
   - Install all Node dependencies
   - Create your `.env` file from `env.example` if needed
   - Optionally bootstrap a local Whisper virtual environment in `.venv-whisper`
   - Launch OpenCluely

3. **First-run Onboarding**:
   - On first launch, the onboarding wizard guides you through selecting your preferred LLM provider (Gemini, OpenRouter, Groq, or Ollama) and speech configuration.
   - Settings are stored securely in your user data directory and persist across application updates.

### 🎛️ Setup Script Options

```bash
./setup.sh --build          # Build distributable installer for your OS
./setup.sh --ci             # Use npm ci instead of npm install
./setup.sh --no-run         # Setup only, do not launch the app
./setup.sh --install-system-deps  # Install system audio dependencies (ffmpeg, sox)
./setup.sh --skip-whisper  # Skip local Whisper virtual environment setup
```

---

## 🎮 How to Use

### 🖱️ **Keyboard Shortcuts**

| Action | Shortcut (macOS) | Shortcut (Windows/Linux) | Description |
|--------|------------------|--------------------------|-------------|
| **Screenshot Capture** | `⌘⇧S` | `Ctrl+Shift+S` | Capture screen and analyze with active mode & LLM |
| **Toggle Speech** | `Alt+R` | `Alt+R` | Start/stop voice recognition |
| **Toggle Visibility** | `⌘⇧V` | `Ctrl+Shift+V` | Show or hide all OpenCluely windows |
| **Toggle Interaction** | `⌘⇧I` or `Alt+A` | `Ctrl+Shift+I` or `Alt+A` | Toggle click-through stealth mode |
| **Switch to Chat** | `⌘⇧C` | `Ctrl+Shift+C` | Open interactive conversation chat |
| **Clear Memory** | `⌘⇧\` | `Ctrl+Shift+\` | Reset conversation memory for a clean slate |
| **Force Always-on-Top** | `⌘⇧T` | `Ctrl+Shift+T` | Re-assert topmost window layer across all displays |
| **Settings** | `⌘,` | `Ctrl+,` | Open the Settings & Configuration window |
| **Cycle Modes** | `⌘↑` / `⌘↓` | `Ctrl+↑` / `Ctrl+↓` | Switch between General, Coding, and Meeting modes (interactive mode) |
| **Nudge Window** | `⌘` + Arrow Keys | `Ctrl` + Arrow Keys | Move overlay windows around the screen (click-through mode) |

### 🎯 **Recommended Workflow**

1. **Launch OpenCluely** → The stealth overlay appears in the corner of your screen.
2. **Select Mode & Language** → Use `⌘↑` / `⌘↓` or the overlay bar to pick **General**, **Coding**, or **Meeting** mode (and choose your target programming language if in Coding mode).
3. **Capture Questions** → Press `⌘⇧S` (`Ctrl+Shift+S`) to capture problem statements, IDE code, or diagrams.
4. **Speak Questions** → Press `Alt+R` or click the mic button to ask questions verbally.
5. **Receive Answers** → The draggable answer window displays optimal solutions, formatted code, and complexity analysis.
6. **Chat & Iterate** → Press `⌘⇧C` to follow up, ask for optimizations, or discuss edge cases.

---

<details markdown="1">
<summary>🧩 <b>Troubleshooting</b></summary>

### Setup Issues

- **`setup.sh` not found or won't run**
  - Make sure you're in the project root: `cd OpenCluely`
  - Make the script executable: `chmod +x setup.sh`
  - On Windows, run within Git Bash or WSL.

- **Node or npm errors**
  - Ensure Node.js 18+ is installed (`node -v`).

### App & Permissions

- **macOS screen capture shows blank images**
  - Grant **Screen Recording** permission in *System Settings → Privacy & Security → Screen Recording*.
  - Restart OpenCluely after granting permission.

- **Microphone / speech recognition issues**
  - macOS: Grant **Microphone** permission in *System Settings → Privacy & Security → Microphone*.
  - Local Whisper: Ensure `ffmpeg` and `sox` are installed on your system PATH (`brew install ffmpeg sox` on macOS, `sudo apt install ffmpeg sox` on Ubuntu).
  - Groq / Azure: Verify your API keys and region settings in `.env` or Settings.

- **Local Ollama connection failure**
  - Verify Ollama is running (`ollama serve` or Ollama desktop app).
  - Check that the model is pulled (`ollama pull llama3.2`).
  - Verify `OLLAMA_HOST` in Settings matches your Ollama instance URL (default: `http://localhost:11434`).

</details>

<details markdown="2">
<summary>⚖️ <b>Legal & Ethics</b></summary>

### 📋 **Disclaimer**

OpenCluely is designed and provided for educational, research, and productivity purposes. Users are responsible for:
- Complying with interview guidelines and honor codes
- Respecting company policies and terms of service
- Using the software ethically and responsibly

### 🔒 **Privacy & Security**

- **No telemetry or background data collection**.
- API communications are sent directly to your chosen provider (Google, OpenRouter, Groq, or Azure).
- When using **Ollama** and **Local Whisper**, all AI inference and audio processing run **100% locally on your machine with zero external network requests**.
- Session history remains stored strictly on your local device.

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

</details>

---

## 🌐 Website

**[opencluely.techycsr.dev](https://opencluely.techycsr.dev)**

---

## 💖 Acknowledgments

- **Google Gemini**: Multimodal AI intelligence via `@google/genai`
- **OpenRouter**: Multi-model routing and LLM flexibility
- **Groq**: Ultra-fast LLM inference, Whisper Large V3 STT, and Orpheus TTS
- **Ollama**: Local, private offline model inference
- **OpenAI Whisper & Azure Speech**: Voice recognition backends
- **Electron**: Cross-platform desktop application framework
- **Vysper**: UI and structure inspiration — see [Vysper by varun-singhh](https://github.com/varun-singhh/Vysper)

---

<div align="center">

⭐ **Star this repo** if OpenCluely helps you ace your interviews or boosts your workflow!

**Made with ❤️ by [TechyCSR](https://techycsr.dev)**

</div>

