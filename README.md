# SREESHNU S A - Personal Portfolio Website

A clean, modern, minimal, responsive personal portfolio website created for placement purposes as an Artificial Intelligence & Data Science engineering student.

Built strictly with **pure HTML5, CSS3, and JavaScript** (No external frameworks, Bootstrap, React, or Tailwind).

---

## 🎨 Design & Aesthetic System
- **Background**: Matte Black (`#0B0B0B`)
- **Cards**: Dark Gray (`#161616`)
- **Primary Accent**: Light Blue (`#38BDF8`)
- **Hover Accent**: Sky Blue (`#60A5FA`)
- **Typography**: [Poppins](https://fonts.google.com/specimen/Poppins) (Google Fonts)
- **Border Radius**: `12px`
- **Animations**:
  - Scroll fade-in (`IntersectionObserver`)
  - Smooth navigation scroll
  - Card hover translation (`translateY(-5px)`)
  - Button hover scale effect
  - Navigation link hover underline animation

---

## 📂 Project Directory Structure

```
portfolio/
├── index.html              # Main HTML document with semantic structure
├── style.css               # Design tokens, responsive grid layout & animations
├── script.js               # Scroll observer, navigation & dynamic interactive logic
├── README.md               # Documentation & setup guide
└── assets/
    ├── images/             # Profile picture and avatar assets
    │   └── profile.jpg
    ├── project-images/     # Project preview cards images
    │   ├── project1.jpg
    │   ├── project2.jpg
    │   └── project3.jpg
    └── resume.pdf          # Resume document for direct download
```

---

## 🚀 How to Run Locally

1. Open a terminal or command prompt in the `portfolio` directory:
   ```bash
   cd portfolio
   ```

2. Start a simple local server:
   - **Python**:
     ```bash
     python -m http.server 8000
     ```
   - Or open `index.html` directly in any web browser.

3. Open your browser and navigate to `http://localhost:8000`.

---

## ✏️ Customization Instructions

1. **Personal Information**: Open `index.html` and replace placeholder email, phone, and social links with your actual details.
2. **Resume**: Replace `assets/resume.pdf` with your updated PDF resume.
3. **Projects**: Edit project titles, descriptions, technology badges, and live demo / GitHub links in the `<section id="projects">` block inside `index.html`.
4. **Profile Picture**: Replace `assets/images/profile.jpg` with your own square photo.
