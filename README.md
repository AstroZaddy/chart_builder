# 🌠 Z13 Astrology · v0.7-beta

> **Real Sky. Real You.**  
> Astrology that reflects the sky *as it actually is* — not how it was 2,000 years ago.

Z13 Astrology is a true sidereal astrology platform built for clarity, precision, and transformation.  
This version marks our **first public beta release** — a fully working MVP that generates natal charts based on **real astronomical constellations**, using a **13-sign system** and **whole sign houses**.

---

## 📂 File Structure

```plaintext
├── api/
│   └── main.py           # FastAPI server routes
├── chart_engine/
│   └── chart_builder.py  # Core chart calculation logic (Z13 system)
├── webui/
│   ├── static/           # CSS, images, assets
│   │   ├── style.css
│   │   ├── z13_logo_gold.png
│   │   └── stars.png
│   ├── templates/
│   │   ├── partials/
│   │   │   ├── nav.html  # Reusable nav bar
│   │   │   └── footer.html
│   │   ├── landing.html
│   │   ├── form.html
│   │   ├── chart.html
│   │   ├── learn.html
│   │   ├── about.html
│   │   ├── subscribe.html
│   │   └── shop.html
├── requirements.txt      # Python dependencies
├── README.md              # This file
└── render.yaml (optional) # For cloud deployment config (Render.com, etc.)

##🚀 Current Features (v0.7-beta)

✅ Real Sky Chart Generation
✅ 13 Signs + Ophiuchus Included
✅ Whole Sign Houses
✅ Responsive Frontend (Mobile + Desktop)
✅ Alpine.js Mobile Navigation
✅ Chart Placements Listed with Retrograde Flags
✅ Starter Informational Pages (Learn, About, Subscribe, Shop)
✅ MVP Launch-Ready Website Structure
✅ Clean, Modular Jinja2 Templates
✅ FastAPI Backend, Static Asset Handling

⸻

## 🌌 Features in Development (v0.8+ Roadmap)

🚧 Email capture + PDF export of natal chart
🚧 Chart wheel diagram (Z13 sidereal version)
🚧 Substack newsletter & community integration
🚧 Swag / merch store (Printful/Printify)
🚧 Tip jar for donations (Ko-fi, Buy Me A Coffee)
🚧 Blog content import from Substack (RSS feed parsing)
🚧 Synastry charts (relationship astrology)
🚧 Transit and progression reporting
🚧 Premium readings and reports

⸻

🛠️ Tech Stack (Requirements)

Component | Stack | 
Backend | Python 3.11+, FastAPI
Frontend | TailwindCSS, Alpine.js, Jinja2 templates
Deployment Ready | Render, Fly.io, DigitalOcean
Chart Engine | Swiss Ephemeris backend (optional for later upgrades)
Optional Tools | WeasyPrint (for PDF export), Substack (newsletter), Stripe (future payments)

## Local Development Setup

Clone the repo
git clone https://github.com/your-username/z13-astrology.git
cd z13-astrology

Create a virtual environment
python -m venv venv
source venv/bin/activate

Install dependencies
pip install -r requirements.txt

Run the dev server:
uvicorn api.main:app --reload

Open in browser:
http://localhost:8000

## 📜 License

MIT — use freely, modify soulfully.

⸻

## ✨ Live Site

🔗 https://z13astrology.com (or deployment link once live)
🚀 Public beta is live — expect updates and stellar expansions soon!

⸻

## 💌 Credits

Created with cosmic precision by @astrozaddy.
Guided by the stars. Fueled by caffeine. Driven by truth.
