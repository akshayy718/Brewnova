<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0,0A0A18,16213E,E94560&height=200&section=header&text=Brewnova%20Café&fontSize=55&fontColor=fff&animation=fadeIn&fontAlignY=36&desc=Midnight%20Espresso%20Theme%20%7C%20Django%20%7C%20Full%20Stack%20%7C%20Live%20on%20PythonAnywhere&descAlignY=58&descSize=16" width="100%"/>
</div>

<div align="center">

[![Live Website](https://img.shields.io/badge/🌐_Live_Website-akshay718.pythonanywhere.com-E94560?style=for-the-badge&logo=django&logoColor=white)](https://akshay718.pythonanywhere.com)
[![Demo Video](https://img.shields.io/badge/🎥_Demo_Video-Watch_Here-16213E?style=for-the-badge&logo=youtube&logoColor=E94560)](#-demo-video)
[![GitHub](https://img.shields.io/badge/GitHub-akshayy718-0A0A18?style=for-the-badge&logo=github&logoColor=white)](https://github.com/akshayy718)

</div>

<div align="center">

![Python](https://img.shields.io/badge/Python-3.13-E94560?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-6.0.6-16213E?style=flat-square&logo=django&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E94560?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-16213E?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-E94560?style=flat-square&logo=javascript&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-0A0A18?style=flat-square&logo=sqlite&logoColor=white)
![PythonAnywhere](https://img.shields.io/badge/PythonAnywhere-Deployed-E94560?style=flat-square&logoColor=white)

</div>

---

## 📌 Overview

**Brewnova Café** is a fully responsive, dark-themed cafe website built with **Django 6.0**, featuring a curated menu of 30+ items, online ordering with VAT calculation, blog reviews with star ratings, and a custom SVG brand identity — all designed with the signature **Midnight Espresso** color palette.

> ☕ *"Where every cup tells a story."*

### 🌐 Live at: **[akshay718.pythonanywhere.com](https://akshay718.pythonanywhere.com)**

---

## 🎥 Demo Video

<div align="center">

| 🎬 Screen Recording | Description |
|---|---|
| [▶️ Click here to watch the demo](#) | Full walkthrough of the Brewnova Café website |

> 📌 *Demo video link coming soon*

</div>

---

## 🎨 Midnight Espresso Theme

<div align="center">

| Element | Color | Hex |
|---------|-------|-----|
| 🌑 **Background** | Deep dark navy | `#0D0D1A` |
| 🖤 **Navbar / Footer** | Near-black | `#0A0A18` |
| 🃏 **Cards** | Dark navy | `#16213E` |
| ❤️ **Accent** | Red-pink | `#E94560` |
| 🤍 **Text** | Light cream | `#F5F5F5` / `#EDEDED` |

</div>

Custom SVG logo featuring a coffee cup with steam lines, dashed border ring, and "BREWNOVA — CAFE & ROASTERY" typography — all in the Midnight Espresso palette.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🏠 **Home Page** | Hero section with signature coffee previews, testimonials, and CTA |
| 📋 **Menu Page** | 30+ items across 5 categories in responsive 3-column grid cards |
| 🛒 **Order Page** | Dynamic order form with item selection, quantity, subtotal, VAT (5%), delivery fee, and payment options (Card / Apple Pay / Cash) |
| 📝 **Blogs Page** | Customer review cards with star ratings and review submission form |
| ℹ️ **About Page** | Brand story, team section, heritage, awards, and visit info |
| 📱 **Responsive** | Fully optimized for mobile, tablet, and desktop |
| 🎨 **Dark Theme** | Custom Midnight Espresso color palette with red-pink accents |
| ☕ **Custom Logo** | SVG coffee cup logo matching brand identity |
| ✨ **Animations** | Fade-in scroll effects on menu cards and sections |
| 🇦🇪 **UAE Context** | AED pricing, Abu Dhabi address, local phone, regional payment methods |

---

## 📋 Menu Categories

| Category | Items | Highlights |
|----------|:-----:|------------|
| 🔥 **Signature Specials** | 6 | Blood Coffee, Brewnova Royale, Saffron Latte |
| ☕ **Coffee Classics** | 9 | Espresso, Cappuccino, Cold Brew, Affogato |
| 🍃 **Tea & Tisanes** | 6 | Masala Chai, Kashmiri Kahwa, Hibiscus Tea |
| 🥤 **Coolers & Shakes** | 6 | Rose Falooda, Mango Tango, Choco Frappe |
| 🍞 **Bites & Bakes** | 6 | Chocolate Lava Cake, Paneer Roll, Brownie |

---

## 🏗️ Architecture

```
┌──────────────────────────────────────────────────────┐
│              Brewnova Café — Django App               │
│                                                       │
│  ┌─────────────────────────────────────────────────┐ │
│  │            Frontend (Browser)                    │ │
│  │   HTML5 Templates · CSS3 Dark Theme · JavaScript │ │
│  └──────────────────────┬──────────────────────────┘ │
│                         │                             │
│                         ▼                             │
│  ┌─────────────────────────────────────────────────┐ │
│  │         Django Backend (Python 3.13)             │ │
│  │                                                  │ │
│  │   urls.py → views.py → templates/               │ │
│  │                                                  │ │
│  │   /         → index.html   (Home)               │ │
│  │   /menu     → menu.html    (Menu)               │ │
│  │   /orders   → orders.html  (Orders)             │ │
│  │   /blogs    → blogs.html   (Blog)               │ │
│  │   /about    → about.html   (About)              │ │
│  └──────────────────────┬──────────────────────────┘ │
│                         │                             │
│                         ▼                             │
│  ┌─────────────────────────────────────────────────┐ │
│  │           SQLite Database · db.sqlite3           │ │
│  └─────────────────────────────────────────────────┘ │
│                                                       │
│  Deployed on PythonAnywhere (WSGI + Static Files)    │
└──────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **Backend** | Python 3.13 + Django 6.0.6 | Web framework, routing, views |
| **Frontend** | HTML5 + CSS3 | Page structure and dark theme styling |
| **Interactivity** | JavaScript | Order form logic, scroll animations |
| **Database** | SQLite | Data storage |
| **Fonts** | Playfair Display + Poppins | Headings + body typography |
| **Icons** | Font Awesome 6 | UI icons across all pages |
| **Deployment** | PythonAnywhere | WSGI + static file serving |
| **Version Control** | Git + GitHub | Source code management |

</div>

---

## 📁 Project Structure

```
Brewnova/
│
├── 📁 Brewnova/               → Django app
│   ├── views.py              → Page view functions
│   ├── urls.py               → URL routing
│   └── models.py             → Data models
│
├── 📁 Brewnova_project/       → Django project settings
│   ├── settings.py           → App configuration
│   ├── urls.py               → Root URL routing
│   └── wsgi.py               → WSGI entry point
│
├── 📁 templates/              → HTML page templates
│   ├── base.html             → Base layout (navbar, footer, logo)
│   ├── index.html            → Home page
│   ├── menu.html             → Menu page (30+ items)
│   ├── orders.html           → Order form with VAT
│   ├── blogs.html            → Reviews + star ratings
│   └── about.html            → Brand story + team
│
├── 📁 static/
│   ├── 📁 css/
│   │   └── style.css         → Midnight Espresso theme (29K+)
│   ├── 📁 js/
│   │   └── script.js         → Order logic + animations
│   └── 📁 images/            → 60+ curated food photos + SVG logo
│
├── 📄 manage.py               → Django management CLI
├── 📄 requirements.txt        → Python dependencies
└── 📄 db.sqlite3             → SQLite database
```

---

## ⚡ Quick Start

### Prerequisites
- Python 3.12+
- pip

### Setup

```bash
# Clone the repository
git clone https://github.com/akshayy718/Brewnova.git
cd Brewnova

# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate          # Windows
source venv/bin/activate       # Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver
```

Open your browser and go to:
```
http://127.0.0.1:8000
```

---

## 🌐 Deployment (PythonAnywhere)

| Step | Action |
|------|--------|
| 1 | Clone repo on PythonAnywhere |
| 2 | Create virtualenv with Python 3.13 |
| 3 | `pip install -r requirements.txt` |
| 4 | `python manage.py collectstatic` |
| 5 | Configure WSGI with `Brewnova_project.settings` |
| 6 | Set static files: `/static/` → `staticfiles/` |
| 7 | Reload web app |

**Live at:** [akshay718.pythonanywhere.com](https://akshay718.pythonanywhere.com)

---

## 🔮 Future Improvements

- [ ] **User Authentication** — Customer login and signup
- [ ] **Payment Integration** — Online payment gateway (Stripe / PayTabs)
- [ ] **Admin Dashboard** — Manage menu items and orders
- [ ] **Email Notifications** — Order confirmation emails
- [ ] **Image Optimization** — Compress images for faster loading

---

## 👨‍💻 Developer

<div align="center">

**Akshay Santhosh** — AI/ML Engineer & Full Stack Developer

[![GitHub](https://img.shields.io/badge/GitHub-akshayy718-0A0A18?style=for-the-badge&logo=github&logoColor=white)](https://github.com/akshayy718)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Akshay%20Santhosh-16213E?style=for-the-badge&logo=linkedin&logoColor=E94560)](https://www.linkedin.com/in/akshay-santhosh-435499208)
[![Email](https://img.shields.io/badge/Gmail-akshaysanthosh718-E94560?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akshaysanthosh718@gmail.com)

</div>

---

<div align="center">

*Built with ☕ and ❤️ using Django · Python · HTML · CSS · JavaScript*

**Midnight Espresso Theme** — `#0A0A18` · `#0D0D1A` · `#16213E` · `#E94560` · `#F5F5F5`

<img src="https://capsule-render.vercel.app/api?type=waving&color=0,E94560,16213E,0A0A18&height=130&section=footer&animation=fadeIn" width="100%"/>

</div>
