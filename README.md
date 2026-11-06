# SAMSN

**Chat with AI models the way you used to chat with friends on MSN Messenger.**

SAMSN is a private, offline-first AI chat app for Linux with the look and feel of MSN Messenger 7.5. Your AI models are your contacts: pick one, type, and the reply streams in like a 2006 chat window, complete with nudges, winks, emoticons and the original sounds.

## Download

Download the newest **`SAMSNV*.deb`** file from the list of files at the top of this page (currently [SAMSNV0.3.49.deb](https://github.com/Samual-M/SAMSN/raw/main/SAMSNV0.3.49.deb)), then install it:

```
sudo apt install ./SAMSNV0.3.49.deb
```

Open **SAMSN** from your apps menu. To update later, download the newest .deb from here and install it the same way; opening the new version closes the old one automatically.

Needs Node.js 18 or newer (`sudo apt install nodejs`) and a Chromium-based browser (Chromium, Chrome, Edge or Brave), which SAMSN uses for its window.

## What it can do

- **Any AI model**: free local models with Ollama, llama.cpp, LM Studio, Jan or GPT4All, or online services such as Claude, OpenAI, Gemini, OpenRouter, Groq, Mistral and DeepSeek (with your own API key). *File › Add a Model* walks you through it.
- **Two themes**: the classic **MSN Messenger 7.5** window (locked layout that scales cleanly to any size) and **MSN Modern** (upscaled icons, rounded bubbles, a roomier layout).
- **Paint built in**: click any picture in a chat to mark it up in Paint, close Paint, and it is back in your message ready to send.
- **Plug-ins**: slash commands (`/calc`, `/summarize`...), prompt packs, looks such as Dark mode, and new AI providers.
- **Fine-tuning** per conversation: creativity, top P/K, penalties, memory size, seed, stop words, plus Precise / Balanced / Creative presets.
- **Memory, instructions, projects and saved prompts**, message editing and retry, formatted replies with code copy buttons, and group chats with several models.

## Privacy

No accounts, tracking, analytics or ads. Everything stays on your computer. SAMSN only connects to the AI services you add yourself, and asks before anything else (model search, the online plug-in list). It never checks for updates by itself. The server listens on 127.0.0.1 only.

## Note on the artwork

The interface uses images, layouts and sounds from Microsoft's MSN Messenger, which remain Microsoft's property. This is a non-commercial fan project for personal use.
