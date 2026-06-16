# ☕ Brewnova Cafe

A fully responsive, dark-themed cafe website built with **Django**, featuring a curated menu, online ordering, blog reviews, and a custom brand identity. Designed with a **Midnight Espresso** color palette and deployed live on **PythonAnywhere**.

🔗 **Live Demo:** [akshay718.pythonanywhere.com](https://akshay718.pythonanywhere.com)

---

## 🖥️ Screenshots

| Page | Description |
|------|-------------|
| **Home** | Hero section with signature coffee previews, testimonials, and CTA |
| **Menu** | 30+ items across 5 categories in responsive 3-column grid cards |
| **About** | Brand story, team section, awards, and visit info |
| **Blogs** | Customer reviews with star ratings and review submission form |
| **Order** | Dynamic order form with item selection, quantity, VAT calculation, and payment options |

---

## 🎨 Theme — Midnight Espresso

| Element | Color |
|---------|-------|
| Background | `#0D0D1A` — Deep dark navy |
| Navbar / Footer | `#0A0A18` — Near-black |
| Cards | `#16213E` — Dark navy |
| Accent | `#E94560` — Red-pink |
| Text | `#F5F5F5` / `#EDEDED` — Light cream |

Custom SVG logo with coffee cup, steam lines, and brand typography.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Backend** | Python · Django 6.0.6 |
| **Frontend** | HTML5 · CSS3 · JavaScript |
| **Styling** | Custom CSS with CSS Variables · CSS Grid · Flexbox |
| **Fonts** | Playfair Display (headings) · Poppins (body) |
| **Icons** | Font Awesome 6 |
| **Deployment** | PythonAnywhere (WSGI · Static Files) |
| **Version Control** | Git · GitHub |

---

## 📁 Project Structure

```
Brewnova/
├── Brewnova/                # Django app (views, urls, models)
│   ├── views.py
│   ├── urls.py
│   └── models.py
├── Brewnova_project/        # Django project settings
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── templates/               # HTML templates
│   ├── base.html
│   ├── index.html
│   ├── menu.html
│   ├── about.html
│   ├── blogs.html
│   └── orders.html
├── static/
│   ├── css/style.css        # Midnight Espresso theme
│   ├── js/script.js         # Order form logic, animations
│   └── images/              # Menu item photos, logo
├── manage.py
└── requirements.txt
```

---

## ✨ Features

- **Responsive Design** — Works on desktop, tablet, and mobile
- **Dark Theme** — Custom Midnight Espresso color palette with red-pink accents
- **Menu System** — 30+ items across 5 categories (Signature Specials, Coffee Classics, Tea & Tisanes, Coolers & Shakes, Bites & Bakes)
- **Online Ordering** — Dynamic order form with item selection, quantity controls, subtotal, VAT (5%), and delivery fee calculation
- **Blog & Reviews** — Customer review cards with star ratings and review submission form
- **Custom Logo** — SVG coffee cup logo designed to match the brand theme
- **Scroll Animations** — Fade-in effects on menu cards and sections
- **UAE Context** — AED pricing, Abu Dhabi address, local phone number, Card/Apple Pay/Cash payment options

---

## 🚀 Getting Started

### Prerequisites
- Python 3.12+
- pip

### Installation

```bash
git clone https://github.com/akshayy718/Brewnova.git
cd Brewnova
python -m venv venv
source venv/bin/activate        # Linux/Mac
venv\Scripts\activate           # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Open **http://127.0.0.1:8000/** in your browser.

---

## 🌐 Deployment (PythonAnywhere)

1. Clone repo on PythonAnywhere
2. Create virtualenv with Python 3.13
3. Install dependencies from `requirements.txt`
4. Run `python manage.py collectstatic`
5. Configure WSGI file with `Brewnova_project.settings`
6. Set static files path: `/static/` → `staticfiles/`
7. Reload web app

---

## 📄 License

This project is for educational and portfolio purposes.

---

## 👤 Author

**Akshay Santhosh**
- GitHub: [@akshayy718](https://github.com/akshayy718)
- LinkedIn: [Akshay Santhosh](https://www.linkedin.com/in/akshay-santhosh-435499208)
- Email: akshaysanthosh718@gmail.com
