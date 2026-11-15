# Hi, I'm Andrew 👋

🎓 Computer Science + Economics, Rutgers University (Class of 2028)<br>
🚀 Building products people actually use

[![Website](https://img.shields.io/badge/Website-0d1117?style=flat-square&logo=googlechrome&logoColor=white)](https://andrewxiao06.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andrewxiao06/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:andrewxiaotoo@gmail.com)

## 🌟 About Me

- Junior studying CS + Economics
- I like building projects that ship to real users and scale
- Currently: working on a video game

## 💡 Projects

### ❤️ R U My Valentine · _Private repo_

![TECH](https://img.shields.io/badge/TECH-555555?style=flat-square)

_A Valentines Day Matchmaker released to 2000+ students_

- _Matching algorithm connecting each person with up to five matches_
- _Users fill out a questionaire to get their personality type, and the most compatable users get paired_
- _Reached 2000+ students exclusively at Rutgers_

### 🏸 ShuttleRank · [Live site](https://shuttlerank.org) · [Repo](https://github.com/andrewxiao06/Shuttlerank)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)

A rating platform for New Jersey badminton club players, live on the web with an iOS app in beta.

- Custom closed-source rating engine with separate singles and doubles ratings and pre-match win-probability forecasts
- Matches only count once every player confirms them; disputed matches block the rating update
- FastAPI + Postgres (Neon) on EC2 behind Caddy, Clerk auth, Next.js web app, and Expo mobile app with push notifications

### 🔎 Sift · [Repo](https://github.com/andrewxiao06/Sift)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_agent-D97757?style=flat-square&logo=anthropic&logoColor=white)

A research agent over ~2,000 arXiv papers that answers the users questions with real citations.

- Hybrid retrieval: BM25 + dense embeddings, fused with Reciprocal Rank Fusion, then reranked by a cross-encoder
- Embedding pipeline written by hand (tokenize → forward pass → mean-pool → normalize) and stored in pgvector
- Every stage graded on a hand-labeled query set: hybrid retrieval hits **0.987 MRR** at about 36 ms per query

### 🏀 NBA Game Predictor · [Repo](https://github.com/andrewxiao06/nba-game-predictor)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5B00?style=flat-square)

Calibrated win probabilities for NBA matchups _(in progress)_.

- Feature engineering in raw SQL with window functions, no ORM, over 10,600+ games
- Leakage-safe features and splits by season, including a "top-5 rotation players available" signal
- Next up: XGBoost baseline, calibration, SHAP explanations, and a FastAPI + Next.js dashboard

### 🧰 More Projects

- **[Menu Translator](https://github.com/andrewxiao06/Menu-Translator)**: point your camera at a foreign menu and get each dish's translation and a one-line explanation (Tesseract OCR + OpenAI)
- **[TFT Monitor](https://github.com/andrewxiao06/TFTMonitor)**: FastAPI service that detects when a Teamfight Tactics game ends and enforces play-time limits

## 🛠️ Tech Stack

![Tech stack](https://skillicons.dev/icons?i=python,ts,js,react,nextjs,fastapi,postgres,sqlite,docker,aws,tailwind,git&perline=12)

🌱 _Always down to talk about side projects, sports analytics, or badminton._
