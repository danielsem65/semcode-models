# 🧠 SemCode Models — Offline AI Model Repository

This repository hosts ready-to-run **`.gguf` model files** for the
[SemCode AI](https://github.com/danielsem65/semcode-ai) Android app.

Everything here runs **100% on your phone** — no internet, no API keys, no servers,
no data leaves your device. Download once, use forever offline.

---

## 📦 Available Models

Grab them from the [**Releases page →**](https://github.com/danielsem65/semcode-models/releases)

| Model | File | Size | RAM needed | Speed | Quality |
|---|---|---|---|---|---|
| Qwen 2.5 **0.5B** Instruct | `qwen2.5-0.5b-instruct-q4_k_m.gguf` | ~400 MB | any phone | ⚡⚡⚡ very fast | ⭐⭐ basic |
| Qwen 2.5 **1.5B** Instruct | `qwen2.5-1.5b-instruct-q4_k_m.gguf` | ~1 GB | 4 GB+ RAM | ⚡⚡ fast | ⭐⭐⭐ good |
| Llama **3.2 3B** Instruct | `llama-3.2-3b-instruct-q4_k_m.gguf` | ~2 GB | 6 GB+ RAM | ⚡ moderate | ⭐⭐⭐⭐ best of the three |

> 💡 **Not sure which to pick?** Start with the **1.5B** — best balance of speed and
> intelligence for most phones. If it feels slow or the app crashes while loading,
> drop down to the 0.5B.

---

## 🚀 How To Use

1. **Download a model** — on your phone, open the
   [Releases page](https://github.com/danielsem65/semcode-models/releases),
   tap the `.gguf` file you want. It lands in your **Downloads** folder.
2. Open **SemCode AI v2.5 or newer**
3. Go to **Settings → AI Providers → On-device (offline)** and expand it
4. Tap **Browse** → navigate to **Downloads** → pick the `.gguf` file
5. Tap **Load** and wait for *"✓ model loaded"*
6. Set **On-device (offline)** as your active provider
7. ✈️ **Turn off WiFi/mobile data and chat — it still works.**

---

## 🛠 Troubleshooting

| Problem | Fix |
|---|---|
| *"model did not load in time"* or app killed | Your phone ran out of RAM — use a smaller model |
| Replies are slow | Normal for phone CPUs — try the 0.5B, close other apps |
| Can't see Downloads in Browse | Grant **All files access**: Settings → Storage card |
| First message after Load is slow | The model warms up on first use — later replies are faster |

---

## 📄 Licenses & Credits

- **Qwen 2.5 (0.5B / 1.5B)** — [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0),
  © Alibaba Cloud · source: [Qwen GGUF collection](https://huggingface.co/Qwen)
- **Llama 3.2 3B** — [Llama 3.2 Community License](https://llama.dev/legal/license),
  © Meta · quantized GGUF by [bartowski](https://huggingface.co/bartowski)

All files are converted to the standard
[GGUF format](https://github.com/ggml-org/llama.cpp/blob/master/docs/build.md) and run via
bundled [llama.cpp](https://github.com/ggml-org/llama.cpp) inside SemCode AI.

---

<p align="center"><i>Built for <a href="https://github.com/danielsem65/semcode-ai">SemCode AI</a> — your pocket AI coding agent.</i></p>
