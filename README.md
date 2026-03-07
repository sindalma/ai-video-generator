# AI Video Generator

**Your personal AI video creator** — turns any text instruction into a professional short video in seconds.

- Nigerian English voice (EzinneNeural)
- Engaging storytelling scripts
- Royalty-free stock footage + automatic subtitles
- Motivational background music
- Posts directly back into Telegram topics

---

### 🚀 Quick Start

1. **Add the bot** → [@AIsindal_bot](https://t.me/AIsindal_bot)
2. **Make the bot Admin** in your group and enable Topics
3. Just type any instruction in a topic, for example:
   - "Motivational video about success in Abuja"
   - "Short video about Lagos traffic"
   - "Make a video of a young man walking confidently to a girl he likes"

The bot will reply in the **same topic** with the finished video.

---

### Tech Stack (Free Tier)

- Groq (LLM for scripts)
- Pexels (stock footage)
- Freesound (background music)
- Edge TTS (Nigerian voice)
- MoviePy + FFmpeg (video editing)
- Hosted on Railway (24/7)

---

### Files in this repo

- `main.py` – Main bot code
- `requirements.txt`
- `nixpacks.toml` – For Railway deployment

---

### Deploy on Railway (One-click)

1. Go to [railway.app](https://railway.app) → New Project → Deploy from GitHub repo
2. Select `sindalma/ai-video-generator`
3. Add these **Environment Variables**:

| Key                | Value                                      |
|--------------------|--------------------------------------------|
| TELEGRAM_TOKEN     | `8787050758:AAFNGmuKUJYsxHMDmdzlqyp4EBzYrQ3ozY4` |
| GROQ_API_KEY       | `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` |
| PEXELS_API_KEY     | `eP1XOvq11b9zQV4oCJNGHZNGmfkgB6di54xIdOk19NQufTXQ1mH3rrfL` |
| FREESOUND_KEY      | `TtvcvWhVgSBjqWT1d9c6nK3YNIcO8fvwxGSo8ff9` |

4. Click **Deploy**

---

**Your bot is now live!**  
Test it right now by sending this in any Telegram topic:

> Make a motivational video about a young handsome boy walking confidently towards a beautiful girl he likes

Let me know when it’s deployed — I’ll give you the next test commands and any tweaks you want.# ai-video-generator
