🇬🇧 [English](#-hi-im-galislavsky) | 🇵🇱 [Polski](#-hej-tu-galislavsky)

# 👋 Hi, I'm Galislavsky

I write Discord bots in Python and set up my own VPS servers to run them.

I learn programming by doing – through my own projects that actually run in production. I use AI tools when coding, but the ideas, testing and deployment are on me.

### 🤖 What I'm working on
**A Discord bot** (discord.py) that runs every day on my server:
- XP and rank system for chat and voice activity
- support tickets and auto-moderation with warnings
- automatic stream and video notifications (Twitch API, YouTube RSS)
- dynamic Join-to-Create voice channels
- image generation (Pillow) and scheduled tasks (`tasks.loop`, asyncio)

**A web leaderboard for the bot** (Flask) – rankings and member profiles in the browser:
- reads the bot's database live, member names and avatars from the Discord API
- Gunicorn behind nginx, HTTPS with Let's Encrypt, own domain

### 🛠️ Tech stack
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![discord.py](https://img.shields.io/badge/discord.py-5865F2?logo=discord&logoColor=white)
![asyncio](https://img.shields.io/badge/asyncio%20%2F%20aiohttp-2C5BB4?logo=aiohttp&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-009688)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?logo=pm2&logoColor=white)
![SSH](https://img.shields.io/badge/SSH-000000?logo=gnubash&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?logo=nginx&logoColor=white)
![Let's Encrypt](https://img.shields.io/badge/Let's%20Encrypt-003A70?logo=letsencrypt&logoColor=white)

### 🖥️ Infrastructure
My own VPS servers (Ubuntu), processes managed with PM2, nginx as a reverse proxy with HTTPS, DNS and domains, secrets kept in `.env`, game server hosting.

---

# 👋 Hej, tu Galislavsky

Piszę boty na Discorda w Pythonie i sam stawiam pod nie serwery na VPS.

Programowania uczę się w praktyce – na własnych projektach, które naprawdę działają. Przy kodzie korzystam z narzędzi AI, ale pomysły, testowanie i wdrażanie są po mojej stronie.

### 🤖 Nad czym pracuję
**Bot na Discorda** (discord.py), który działa na co dzień na moim serwerze:
- system XP i rang za aktywność na czacie i kanałach głosowych
- tickety dla supportu i auto-moderacja z ostrzeżeniami
- automatyczne powiadomienia o streamach i filmach (Twitch API, YouTube RSS)
- dynamiczne kanały głosowe Join-to-Create
- generowanie grafik (Pillow) i zadania cykliczne (`tasks.loop`, asyncio)

**Ranking www dla bota** (Flask) – rankingi i profile członków w przeglądarce:
- czyta bazę bota na bieżąco, nicki i avatary pobiera z Discord API
- Gunicorn za nginx, HTTPS z Let's Encrypt, własna domena

### 🖥️ Infrastruktura
Własne serwery VPS (Ubuntu), procesy pod PM2, nginx jako reverse proxy z HTTPS, DNS i domeny, zmienne środowiskowe w `.env`, hostowanie serwerów gier.
