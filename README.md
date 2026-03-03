# Gayal C Ashok — AI/ML Data Scientist Portfolio

A modern, dark-themed personal portfolio website showcasing skills, projects, certifications, and work experience as an AI/ML Data Scientist.

![Portfolio Screenshot](images/image_png_0001.png)

---

## ✨ Features

- **Interactive Space Background** — Three.js powered star field with fluid cursor effects
- **Typing Animation** — Dynamic role titles with typewriter effect
- **Scrolling Certifications** — Auto-scrolling marquee showcasing certificates with PDF view overlays
- **Project Showcase** — Detailed project cards with links to GitHub repos and live demos
- **Responsive Design** — Fully responsive layout for desktop, tablet, and mobile
- **Smooth Scroll Reveal** — Elements animate into view as you scroll down the page

---

## 🛠️ Technologies Used

| Category        | Technologies                              |
|-----------------|-------------------------------------------|
| **Frontend**    | HTML5, CSS3, JavaScript (ES6+)            |
| **3D / Canvas** | Three.js (star field background)          |
| **Fonts**       | Google Fonts — Syne, DM Sans              |
| **Design**      | Glassmorphism, CSS gradients, animations  |
| **Hosting**     | GitHub Pages (static site)                |

---

## 📁 Folder Structure

```
portfolio-website/
├── index.html              # Main single-page HTML (styles + scripts inline)
├── README.md               # This file
├── .gitignore              # Excludes temp & debug files
├── assets/
│   ├── certificates/       # PDF certificate files
│   │   ├── Certificate-AI.pdf
│   │   ├── Certificate-Data-Science-using-Python-&-R-Programming.pdf
│   │   ├── Certificate-Data-science.pdf
│   │   ├── Certificate-nasscom-data-science.pdf
│   │   ├── Certificate-nasscom-python.pdf
│   │   ├── Certificate-Power-bi.pdf
│   │   ├── Certificate-Pyhon.pdf
│   │   ├── Certificate-SQL.pdf
│   │   ├── Certificate-SUNY.pdf
│   │   ├── Certificate-Tableau.pdf
│   │   ├── Degree.pdf
│   │   ├── Project_1.pdf
│   │   ├── Project_2.pdf
│   │   └── TATA_Gen-AI.pdf
│   └── CV/
│       └── Gayal_Ashok_AI_ML_Data_Scientist.pdf
└── images/                 # Thumbnails, project covers, certificate previews
    ├── image_jpg_*.jpg     # Certificate thumbnail images
    ├── image_png_*.png     # Project cover images & icons
    └── degree_thumb.jpg    # Degree certificate thumbnail
```

---

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Gayal-C-Ashok/portfolio-website.git
   cd portfolio-website
   ```

2. **Open in browser:**
   - Simply open `index.html` in any modern web browser.
   - Or use a local server for best results:
     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node.js
     npx serve .
     ```
   - Then visit `http://localhost:8000`

> **Note:** No build step or package installation is required. This is a fully static single-page website.

---

## 📄 License

© 2025 Gayal C Ashok. All rights reserved.

---

## 🙏 Credits

- **Three.js** — 3D star field background ([threejs.org](https://threejs.org))
- **Google Fonts** — Typography ([fonts.google.com](https://fonts.google.com))
- **Design Inspiration** — Modern glassmorphism portfolio trends
