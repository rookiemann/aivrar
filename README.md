# Hey, I'm aivrar

I build **portable, zero-install AI tools for Windows** — the kind you can drop on a USB stick, double-click, and just use. No Docker, no Python installs, no admin rights, no PATH headaches.

Everything I make is designed to lower the barrier to running AI locally.

---

### What I'm Working On

| Project | What It Does | |
|---------|-------------|--|
| [**LocalSoundsAPI**](https://github.com/rookiemann/LocalSoundsAPI) | Portable offline audio studio — TTS (XTTS, Fish Speech, Kokoro), music gen (Stable Audio, ACE-Step), voice cloning, transcription, video production. Web UI + REST API. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| [**ComfyUI Portable Installer**](https://github.com/rookiemann/comfyui-portable-installer) | One-click ComfyUI setup with multi-GPU support, 101 pre-built models, 16 curated custom nodes, and SageAttention. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| [**Auto Portable Python Deployer**](https://github.com/rookiemann/auto-portable-python-deployer) | Self-bootstrapping tool that generates fully portable Python deployment packages. Supports Python 3.10–3.14 with GUI and CLI. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| [**ImageBuddy**](https://github.com/rookiemann/ImageBuddy) | Stock image search, batch download, and AI captioning (Florence-2) with multi-GPU parallel processing and REST API. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| [**n8n + Python Portable**](https://github.com/rookiemann/n8n-python-portable) | n8n 1.123.5 + Python 3.14 bundled into one folder. Extract, run, done. Python Code node works instantly. | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| [**llama-cpp-python Wheel**](https://github.com/rookiemann/llama-cpp-python-py314-cuda131-wheel) | Pre-built GPU-accelerated llama-cpp-python wheel for Python 3.14 + CUDA 13.1. | ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white) |

---

### The Common Thread

All my projects share the same philosophy:

- **Zero dependencies** — no system Python, no Git, no Docker, no CUDA toolkit to install
- **No admin rights** — everything runs in user space
- **Fully portable** — copy the folder anywhere and it still works
- **Offline-capable** — works without internet after first setup
- **Clean removal** — delete the folder, done

I use Python's embeddable distribution as the foundation and bootstrap everything (pip, tkinter, site-packages) from scratch using only PowerShell and batch scripts.

---

### Tech & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

---

*Built with [Claude Code](https://claude.ai/claude-code) as my AI pair programmer.*
