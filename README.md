## **Shashank’s Portfolio Website**

A **modern, responsive portfolio website** highlighting Aravinth’s skills, projects in **Software Development Engineering (SDE)** and **Data Science & Machine Learning (DS/ML)**.

🔗 [Portfolio Link](https://shashank-portfolio-rose.vercel.app/)

---

### **Key Features**

* **Responsive Design:** Works across devices (desktop, tablet, mobile).
* **Light/Dark Mode:** Toggle theme dynamically.
* **Interactive UI:** Smooth animations and transitions enhance UX.
* **Resume Section:** Multiple versions for different career paths (SDE vs DS/ML).
* **Project Showcase:** Filterable gallery for projects.
* **Publications & Certifications:** Highlights academic and professional achievements.
* **Contact Form:** Simplified way for visitors to reach out.

---

### **Technology Stack**

* **HTML5**
* **CSS3** (Flexbox, Grid, custom properties, component-based)
* **Vanilla JavaScript (ES6+)**
* **Component-based architecture**
* **Font Awesome** (icons)
* **Google Fonts**
* **Formspree** (form submissions)

---

### **CSS Organization**

* **base.css:** Core styles, resets, CSS variables.
* **common.css:** Shared styles across components (headings, animations, utilities).
* **responsive.css:** All media queries and responsive adaptations.
* **components/**: Component-specific CSS (header.css, hero.css, about.css, etc.).
  
```

* **Dark Mode:** Uses a `.dark-mode` class on `<body>` with component-specific overrides.
* **Best Practices:**

  * Use CSS variables.
  * BEM naming convention.
  * Responsive styles only in `responsive.css`.
  * Shared components in `common.css`.

---

### **Project Structure**

```
portfolio/
├── index.html
├── css/
│   ├── base.css
│   ├── common.css
│   ├── responsive.css
│   └── components/...
├── components/...
├── js/
│   ├── main.js
│   └── template-engine.js
├── assets/
│   ├── favicon.svg
│   ├── images/
│   ├── projects/
│   └── resumes/
```

---

### **Setup & Deployment**

* **Hosting:** GitHub Pages

  1. Fork repository
  2. Enable GitHub Pages in settings
  3. Access via: `https://aravinthvr.github.io/portfolio`
* **Local Development:**

  1. Clone repository
  2. Open `index.html` in browser

---

### **Customization**

* Replace profile image in `assets/images/`.
* Replace resume PDFs in `assets/resumes/`.
* Modify projects in HTML.
* Customize colors via CSS variables (`base.css`).

---


### **License**

* **Creative Commons Attribution 4.0 International**
* Free to use, modify, and share with **credit to Shashank.S.**

---

## 📬 Contact

For questions or suggestions, reach out at:
📧 **shashankshatraboina@gmail.com**

---




