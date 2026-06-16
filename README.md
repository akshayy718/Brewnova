<div align="center">

<br/>

<img src="https://raw.githubusercontent.com/akshayy718/Brewnova/main/static/images/brewnova-logo.svg" width="180" height="180" alt="Brewnova Logo"/>

<br/><br/>

# `B R E W N O V A`

### ━━━ *Café & Roastery* ━━━

<br/>

**A dark-themed, fully responsive café website**
**built with Django — live on PythonAnywhere**

<br/>

[<img src="https://img.shields.io/badge/▶%20%20LIVE%20WEBSITE-akshay718.pythonanywhere.com-E94560?style=for-the-badge&labelColor=0A0A18" height="35"/>](https://akshay718.pythonanywhere.com)
&nbsp;&nbsp;
[<img src="https://img.shields.io/badge/▶%20%20DEMO%20VIDEO-Watch%20Walkthrough-16213E?style=for-the-badge&labelColor=0A0A18&logo=googledrive&logoColor=E94560" height="35"/>](https://drive.google.com/file/d/1oscpLaeHALSRTYQPnyXWFAlQk9K1nxEc/view?usp=sharing)

<br/>

<img src="https://img.shields.io/badge/django-6.0.6-E94560?style=flat&labelColor=0D0D1A&logo=django&logoColor=E94560" />
<img src="https://img.shields.io/badge/python-3.13-E94560?style=flat&labelColor=0D0D1A&logo=python&logoColor=E94560" />
<img src="https://img.shields.io/badge/theme-midnight%20espresso-E94560?style=flat&labelColor=0D0D1A" />
<img src="https://img.shields.io/badge/status-live-E94560?style=flat&labelColor=0D0D1A" />
<img src="https://img.shields.io/badge/menu%20items-33+-E94560?style=flat&labelColor=0D0D1A" />

<br/><br/>

---

</div>

<br/>

> *"Where every cup tells a story."*
>
> Brewnova is not just a café website — it's a complete dark-themed web experience with 33+ curated menu items, online ordering with VAT calculation, customer reviews, and a custom brand identity. Every pixel is tuned to the **Midnight Espresso** palette.

<br/>

## `01` — What is this?

A production-grade café website deployed live, featuring five fully designed pages — Home, Menu, About, Blog, and Order — with a custom dark color palette, SVG branding, scroll animations, and UAE-localized content including AED pricing and regional payment options.

**Not a template.** Every color, every card, every menu item was hand-crafted.

> 🌐 **Live Website:** [akshay718.pythonanywhere.com](https://akshay718.pythonanywhere.com)
>
> 🎥 **Demo Video:** [Watch Full Walkthrough on Google Drive](https://drive.google.com/file/d/1oscpLaeHALSRTYQPnyXWFAlQk9K1nxEc/view?usp=sharing)

<br/>

## `02` — The Midnight Espresso palette

```
 ██████  #0A0A18   navbar, footer — near-black
 ██████  #0D0D1A   page background — deep dark navy
 ██████  #16213E   cards, surfaces — dark navy
 ██████  #E94560   accent, prices, links — red-pink
 ██████  #F5F5F5   headings, primary text — cream white
 ██████  #EDEDED   body text — soft gray
```

Custom SVG logo with coffee cup, steam lines, dashed ring, and brand typography — all in palette.

<br/>

## `03` — Pages

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   /            Home         Hero + previews + testimonials  │
│   /menu        Menu         33 items · 5 categories · grid  │
│   /about       About        Story · team · heritage · visit │
│   /blogs       Reviews      Star ratings · submission form  │
│   /orders      Order        Items + qty + VAT + payment     │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

<br/>

## `04` — The menu

```
  🔥  SIGNATURE SPECIALS  ·····  6 items
      Blood Coffee · Brewnova Royale · Filter Reimagined
      Spiced Cocoa Storm · Saffron Latte · Midnight Mocha

  ☕  COFFEE CLASSICS  ·········  9 items
      Espresso · Americano · Cappuccino · Latte · Flat White
      Cold Brew · Mocha · Affogato · Caramel Macchiato

  🍃  TEA & TISANES  ···········  6 items
      Masala Chai · Elaichi Chai · Green Tea
      Kashmiri Kahwa · Hibiscus Tea · Mint Green Tea

  🥤  COOLERS & SHAKES  ········  6 items
      Rose Falooda · Mango Tango · Choco Frappe
      Classic Cold Coffee · Strawberry Shake · Banana Caramel Shake

  🍞  BITES & BAKES  ···········  6 items
      Chocolate Lava Cake · Banana Walnut Loaf · Choc Chip Cookie
      Cheese Toast · Paneer Roll · Brownie
```

Every section has item counts divisible by 3 — perfect 3-column grid alignment on desktop.

<br/>

## `05` — Features

```
  ✦  Dark theme          Custom Midnight Espresso palette — not a template
  ✦  33+ menu items      Across 5 categories with curated food photography
  ✦  Online ordering     Item select → quantity → subtotal → VAT 5% → total
  ✦  Star ratings        Customer reviews with 5-star rating system
  ✦  SVG logo            Custom coffee cup logo matching brand identity
  ✦  Scroll animations   Fade-in effects on cards as you scroll
  ✦  Responsive          Works on mobile, tablet, and desktop
  ✦  UAE localized       AED pricing · Abu Dhabi address · Card/ApplePay/Cash
  ✦  Live deployment     Running on PythonAnywhere with static file serving
```

<br/>

## `06` — Tech

```
  Backend ............. Python 3.13 · Django 6.0.6
  Frontend ............ HTML5 · CSS3 (CSS Variables · Grid · Flexbox)
  Interactivity ....... Vanilla JavaScript
  Typography .......... Playfair Display (headings) · Poppins (body)
  Icons ............... Font Awesome 6
  Database ............ SQLite
  Deployment .......... PythonAnywhere (WSGI + Static Files)
  Version Control ..... Git · GitHub
```

<br/>

## `07` — Project structure

```
Brewnova/
│
├── Brewnova/                  ← Django app
│   ├── views.py                  page views
│   ├── urls.py                   route mapping
│   └── models.py                 data models
│
├── Brewnova_project/          ← Django project config
│   ├── settings.py               configuration
│   ├── urls.py                   root urls
│   └── wsgi.py                   WSGI entrypoint
│
├── templates/                 ← HTML pages
│   ├── base.html                 layout + navbar + footer
│   ├── index.html                home
│   ├── menu.html                 menu (33 items)
│   ├── orders.html               order form + VAT
│   ├── blogs.html                reviews + ratings
│   └── about.html                story + team
│
├── static/
│   ├── css/style.css             midnight espresso theme
│   ├── js/script.js              order logic + animations
│   └── images/                   60+ photos + SVG logo
│
├── manage.py
├── requirements.txt
└── db.sqlite3
```

<br/>

## `08` — Run it locally

```bash
git clone https://github.com/akshayy718/Brewnova.git
cd Brewnova

python -m venv venv
venv\Scripts\activate              # windows
source venv/bin/activate           # mac/linux

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Open → **http://127.0.0.1:8000**

<br/>

## `09` — Deploy to PythonAnywhere

```
  1.  Clone repo on PythonAnywhere
  2.  Create venv with Python 3.13
  3.  pip install -r requirements.txt
  4.  python manage.py collectstatic
  5.  Configure WSGI → Brewnova_project.settings
  6.  Static files: /static/ → staticfiles/
  7.  Remove whitenoise from MIDDLEWARE (PythonAnywhere serves static natively)
  8.  Reload → live
```

<br/>

## `10` — What's next

```
  □  User authentication — login, signup, order history
  □  Payment gateway — Stripe or PayTabs integration
  □  Admin dashboard — manage menu items and orders
  □  Email notifications — order confirmation
  □  Image optimization — compress for faster loading
```

<br/>

---

<div align="center">

<br/>

<img src="https://raw.githubusercontent.com/akshayy718/Brewnova/main/static/images/brewnova-logo.svg" width="60" height="60" alt="Brewnova"/>

<br/>

**Built by [Akshay Santhosh](https://github.com/akshayy718)**

[<img src="https://img.shields.io/badge/github-akshayy718-0A0A18?style=flat-square&logo=github&logoColor=E94560" />](https://github.com/akshayy718)
[<img src="https://img.shields.io/badge/linkedin-akshay%20santhosh-0A0A18?style=flat-square&logo=linkedin&logoColor=E94560" />](https://www.linkedin.com/in/akshay-santhosh-435499208)
[<img src="https://img.shields.io/badge/email-akshaysanthosh718-0A0A18?style=flat-square&logo=gmail&logoColor=E94560" />](mailto:akshaysanthosh718@gmail.com)

<br/>

`#0A0A18` · `#0D0D1A` · `#16213E` · `#E94560` · `#F5F5F5`

**midnight espresso**

<br/>

</div>
