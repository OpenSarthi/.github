<div align="center">

# OpenSarthi

### Open-source AI desktop operator for voice, automation, and native system control.

<img src="https://raw.githubusercontent.com/OpenSarthi/opensarthi/main/assets/logo.png" width="180" alt="OpenSarthi Logo"/>

</div>

---

## Vision

OpenSarthi is building an AI-native desktop runtime focused on:

- Voice-first interaction
- Native desktop automation
- Accessibility-aware system control
- Generalized computer-use primitives
- Cross-platform AI agents

The goal is to create an intelligent desktop operator that works naturally across Linux, and later Windows and macOS.

---

## Core Principles

- OS-first, not browser-first
- Local-first runtime architecture
- Lightweight native desktop experience
- Accessibility-tree-driven automation
- Secure and sandboxed execution
- Open-source and extensible

---

## Tech Stack

### Desktop
- Tauri v2
- React
- TypeScript
- Rust

### Runtime
- Python 3.12+
- FastAPI
- PydanticAI

### Voice
- Faster Whisper
- OpenWakeWord
- Kokoro / Piper TTS

### Automation
- AT-SPI
- xdotool / ydotool
- OpenCV
- Tesseract OCR

### AI
- Ollama
- OpenRouter
- DeepSeek
- Qwen
- Gemini

---

## Architecture

```text
Tauri Desktop Shell
        ↓
Rust Native Core
        ↓
Python AI Runtime
        ↓
Automation Providers
        ↓
Linux Desktop / System APIs
```

---

## Current Focus

We are currently focused on:

- Linux-native desktop automation
- Voice interaction pipeline
- Accessibility-tree integration
- Generalized tool execution
- AI planning runtime

---

## Repositories

| Repository | Description |
|---|---|
| `opensarthi` | Main monorepo |
| `docs` | Documentation and architecture |
| `sdk` | Future SDK and integrations |

---

## Long-Term Goals

- Cross-platform desktop agents
- AI-native workflows
- Persistent memory systems
- Visual desktop understanding
- Autonomous task execution
- Extensible plugin ecosystem

---

## Contributing

OpenSarthi is in active early-stage development.

Contributions, ideas, architecture discussions, and experiments are welcome.

---

<div align="center">

### "Hey Sarthi"

Building the future of AI-native desktop computing.

</div>
