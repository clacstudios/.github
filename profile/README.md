# 🎵 CLAC Studios

**Cole's Lossless Audio Codec Ecosystem** - A complete audio compression solution built from scratch

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)
![Stars](https://img.shields.io/github/stars/clacstudios/clac-studios.svg)

---

## 🌟 Overview

**CLAC Studios** is a complete lossless audio compression ecosystem built entirely from scratch in Python. This repository contains everything you need to compress, decompress, and play audio using the custom **CLAC** (Custom Lossless Audio Codec) format.

### Why CLAC?

| Feature | CLAC | FLAC | ALAC |
|---------|------|------|------|
| **Open Source** | ✅ Yes | ✅ Yes | ❌ Apple |
| **Pure Python** | ✅ Yes | ❌ C | ❌ C |
| **Educational** | ✅ Designed for learning | ❌ Production-focused | ❌ Production-focused |
| **Streaming** | ✅ Built-in | ⚠️ Limited | ⚠️ Limited |
| **Simplicity** | ✅ Easy to understand | ❌ Complex | ❌ Complex |
| **Compression** | Good (30-60%) | Excellent (40-70%) | Excellent (40-70%) |

**CLAC is perfect for:**
- 🎓 Learning audio compression fundamentals
- 🧪 Experimenting with codec design
- 📚 Educational projects and demonstrations
- 🛠 Building custom audio applications

---

## 📦 Projects

This organization contains two main projects:

### 1. [CLAC Codec](https://github.com/clacstudios/clac) 🎯

The core compression library - pure Python lossless audio codec.

```python
from clac import CLACCodec

codec = CLACCodec()
codec.encode("song.wav", "song.clac")  # Compress
codec.decode("song.clac", "song.wav")  # Decompress
```

### 2. [CLAC Studio](https://github.com/clacstudios/clac-studio) 🖥️ ⭐ **Featured**

**Desktop application for encoding, decoding, and playing CLAC files.**

```bash
python clac-studio.py
