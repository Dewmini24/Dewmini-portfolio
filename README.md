# 🌟 Dewmini Pathirana - Portfolio

A modern, responsive, and professional portfolio website showcasing my skills, projects, education, and experience as a Full-Stack Developer.

**Live Demo:** [GitHub Repository](https://Dewmini24.github.io/Dewmini-portfolio)  
**Contact:** [dewminipathirana04@gmail.com](mailto:dewminipathirana04@gmail.com)

---

## 📋 Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Project Structure](#project-structure)
- [Pages Overview](#pages-overview)
- [Installation](#installation)
- [Customization](#customization)
- [CSS Features](#css-features)
- [Responsive Design](#responsive-design)
- [Deployment](#deployment)
- [Contact](#contact)

---

## ✨ Features

### **Modern Design**
- 🎨 Professional gradient color scheme (Purple & Pink)
- 📱 Fully responsive on all devices
- ✨ Smooth animations and hover effects
- 🌙 Light theme with elegant styling

### **Interactive Elements**
- 🔗 Social media links with icons
- 💬 Contact form with validation
- 🎯 Smooth scrolling navigation
- ⌨️ Keyboard-friendly interface

### **Content Sections**
- 👤 Home page with hero section
- ℹ️ About me with skills showcase
- 📚 Education timeline with modern design
- 🏆 Certifications display
- 💼 Professional experience & projects
- 📧 Contact section

### **Professional Features**
- 📊 Technical skills with progress bars
- 🎓 Education timeline with animated dots
- 🧠 Soft skills with emoji icons
- 🌐 Multi-page navigation
- 📱 Mobile-first approach

---

## 🛠️ Technologies

### **Frontend**
- HTML5 - Semantic markup
- CSS3 - Modern styling with variables
- JavaScript - Interactive features
- Font Awesome Icons - Professional icons

### **Design Tools**
- CSS Variables - Color management
- Flexbox & Grid - Responsive layouts
- CSS Animations - Smooth transitions
- Gradients - Modern visual effects

### **Deployment**
- GitHub Pages - Static site hosting
- Git - Version control
- GitHub - Repository hosting

### **Fonts**
- Playfair Display - Elegant headings
- Poppins - Clean body text
- Google Fonts - Font hosting

---

## 📁 Project Structure

```
Dewmini-portfolio/
│
├── pages/
│   ├── index.html          # Home page
│   ├── about.html          # About page with skills
│   ├── projects.html       # Projects & experience
│   └── contact.html        # Contact & newsletter
│
├── css/
│   └── style.css           # Main stylesheet (complete)
│
├── images/
│   ├── Dewmini-Portfolio Home.png    # Home profile image
│   └── Dewmini-Portfolio About.png   # About page image
│
├── README.md               # This file
```

---

## 📄 Pages Overview

### **1. Home Page (index.html)**
**Location:** `/pages/index.html`

**Content:**
- Hero section with profile image (left side)
- Introduction text
- Call-to-action buttons
- Social media links with icons
- Featured projects showcase
- Quick contact section

**Features:**
- Profile image on left (280px, circular, with hover effect)
- Social links: GitHub, LinkedIn, Email
- View My Work & Get in Touch buttons
- Recent project cards
- Professional appearance

---

### **2. About Page (about.html)**
**Location:** `/pages/about.html`

**Content:**
- Centered profile photo
- About me description
- Technical skills (organized by category)
- Soft skills showcase
- Education timeline
- Certifications

**Skills Categories:**
1. **Frontend Development** - React, JavaScript, HTML5, CSS3
2. **Backend Development** - Node.js, Java, Python, REST APIs
3. **Database & Tools** - MongoDB, SQL, Git, Firebase

**Soft Skills:**
- Problem Solving 💡
- Teamwork 🤝
- Communication 💬
- UI/UX Design 🎨
- Critical Thinking 🧠
- Continuous Learning 📚

---

### **3. Projects Page (projects.html)**
**Location:** `/pages/projects.html`

**Projects Featured:**
1. **EduMath LK** - Full-Stack Learning Platform
   - Technologies: Node.js, React.js, Socket.io, MongoDB
   - GitHub: [Tharumika/edumathlk](https://github.com/Tharumika/edumathlk)

2. **Smart Campus REST API** - Backend API
   - Technologies: Java, JAX-RS, Jersey, Maven
   - GitHub: [Dewmini24/SmartCampusAPI](https://github.com/Dewmini24/SmartCampusAPI)

3. **Personal Portfolio** - This Website
   - Technologies: HTML5, CSS3, JavaScript, GitHub
   - GitHub: [Dewmini24/Dewmini-portfolio](https://github.com/Dewmini24/Dewmini-portfolio)

---

### **4. Contact Page (contact.html)**
**Location:** `/pages/contact.html`

**Content:**
- Newsletter subscription form
- Contact form (name, email, subject, message)
- Contact information (email, LinkedIn, GitHub)
- Social media quick links

**Form Fields:**
- Newsletter: Name, Email
- Contact: Name, Email, Subject, Message

---

## 🚀 Installation

### **Prerequisites**
- Web browser (Chrome, Firefox, Safari, Edge)
- Git (for cloning)
- Code editor (VS Code recommended)

### **Step 1: Clone Repository**
```bash
git clone https://github.com/Dewmini24/Dewmini-portfolio.git
cd Dewmini-portfolio
```

### **Step 2: Open in Browser**
```bash
# Simple way - double-click index.html
# Or use live server in VS Code
```

### **Step 3: View Locally**
- Open `pages/index.html` in your browser
- Or use VS Code Live Server extension
- Navigate using the menu
---

## 🎨 Customization

### **Change Profile Images**

1. **Home Page Image:**
   - Replace: `images/Dewmini-Portfolio Home.png`
   - Size recommended: 280px × 280px
   - Format: PNG with transparent background
   - Update HTML: `src="../images/Dewmini-Portfolio Home.png"`

2. **About Page Image:**
   - Replace: `images/Dewmini-Portfolio About.png`
   - Size recommended: 350px × auto
   - Format: PNG or JPG
   - Update HTML: `src="../images/Dewmini-Portfolio About.png"`

### **Update Personal Information**

**In all HTML files, update:**
```html
<!-- Name -->
<h1>Hi, I'm <span class="highlight">Your Name</span></h1>

<!-- Title -->
<p class="intro-text">Your Title Here</p>

<!-- Contact Links -->
<a href="https://github.com/your-username">GitHub</a>
<a href="https://linkedin.com/in/your-profile">LinkedIn</a>
<a href="mailto:your-email@gmail.com">Email</a>
```

### **Update Projects**

In `projects.html`, modify project cards:
```html
<article class="featured-card">
    <h3>Your Project Name</h3>
    <p>Project description here</p>
    <p><strong>Tech:</strong> Your technologies</p>
    <a href="your-github-link">View Project →</a>
</article>
```

### **Update Skills**

In `about.html`, modify skill items:
```html
<div class="skill-item">
    <div class="skill-icon-wrapper">
        <i class="fab fa-your-icon"></i>
    </div>
    <div class="skill-name">Skill Name</div>
    <div class="skill-bar">
        <div class="skill-fill" style="width: 85%"></div>
    </div>
    <div class="skill-level">85%</div>
</div>
```

### **Change Colors**

In `css/style.css`, update CSS variables:
```css
:root {
    --color-dark-purple: #250e2c;
    --color-purple: #837ab6;
    --color-bright-pink: #f6a5c0;
    /* Change to your colors */
}
```

### **Fonts**

In `pages/index.html` (in head):
```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font:wght@400;600;700&display=swap" rel="stylesheet">
```

Then update in `css/style.css`:
```css
--font-heading: 'Your Font', serif;
--font-body: 'Your Font', sans-serif;
```

---

## 🎯 CSS Features

### **CSS Variables**
```css
:root {
    --color-dark-purple: #250e2c;
    --color-purple: #837ab6;
    --color-bright-pink: #f6a5c0;
    --font-heading: 'Playfair Display', serif;
    --font-body: 'Poppins', sans-serif;
    /* And more... */
}
```

### **Selectors Used**
- Element selectors: `h1`, `p`, `a`
- Class selectors: `.btn`, `.hero`, `.skill-item`
- Pseudo-classes: `:hover`, `:focus`, `:valid`
- Pseudo-elements: `::before`, `::after`
- Child combinator: `.nav-menu > li`
- Negation: `:not(:last-child)`
- Nth-child: `:nth-child(odd)`

### **Features**
- Flexbox & Grid layouts
- Gradients & shadows
- Animations & transitions
- Responsive design
- CSS custom properties
- Media queries
- Transform effects

---

## 📱 Responsive Design

### **Breakpoints**

| Device | Width | Adjustments |
|--------|-------|------------|
| Desktop | 1200px+ | Full layout |
| Tablet | 768px | Reduced spacing, stacked sections |
| Mobile | 480px | Single column, larger touch targets |

### **Responsive Features**
- Mobile-first approach
- Flexible layouts using Flexbox
- Responsive grids with auto-fit
- Font size adjustments
- Image scaling
- Touch-friendly buttons

### **Test Responsiveness**
```bash
# Chrome DevTools
F12 → Toggle device toolbar (Ctrl+Shift+M)
# Test at: 480px, 768px, 1200px
```

---

## 📊 Education Section

### **Modern Timeline Design**
- Vertical gradient line connecting items
- Interactive timeline dots (🎓 emoji)
- Hover animations (slide + scale + shadow)
- Gradient backgrounds
- Professional typography

### **Content:**
1. **BSc Computer Science**
   - University of Westminster (UK) | IIT (Sri Lanka)
   - September 2024 – 2028

2. **Foundation Certificate**
   - Informatics Institute of Technology
   - September 2023 – June 2024

---

## 🏆 Skills Showcase

### **Technical Skills**
- Frontend: React, JavaScript, HTML5, CSS3
- Backend: Node.js, Java, Python
- Database: MongoDB, SQL, Firebase
- Tools: Git, GitHub, REST APIs

### **Soft Skills**
- Problem solving
- Team collaboration
- Communication
- UI/UX design
- Critical thinking
- Continuous learning

---


## 📞 Contact

**Email:** [dewminipathirana04@gmail.com](mailto:dewminipathirana04@gmail.com)  
**GitHub:** [Dewmini24](https://github.com/Dewmini24)  
**LinkedIn:** [Dewmini Pathirana](https://www.linkedin.com/in/dewmini-pathirana-28558a332/)

---

## 🎓 Course Information

**Module:** 5COSC026W Advanced Client-Side Web Development  
**Institution:** Informatics Institute of Technology (IIT), Sri Lanka  
**University:** University of Westminster, UK  
**Student ID:** w2120186  
**Level:** Level 5 (Final Year)

---

## 📚 Resources Used

- [Google Fonts](https://fonts.google.com/)
- [Font Awesome Icons](https://fontawesome.com/)
- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [Web.dev](https://web.dev/)

---

**Made with ❤️ by Dewmini Pathirana**  
**GitHub:** [Dewmini24/Dewmini-portfolio](https://github.com/Dewmini24/Dewmini-portfolio)
