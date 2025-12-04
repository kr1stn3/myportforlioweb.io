📌 Developer Portfolio — README
🌐 Developer Portfolio Website

A modern, animated, and fully responsive developer portfolio built with HTML, TailwindCSS, and custom JavaScript.
This project showcases a complete personal portfolio including: hero section, work/projects, skills, experience timeline, and a demo contact form.

🚀 Live Features
✔ Elegant UI

A modern gradient UI with glassmorphism, glowing effects, smooth animations, and responsive layout.

✔ Sections Included

Hero Section – Intro, availability status & branding

Selected Work – Filterable project gallery (Web / Mobile)

About Section – Personal intro + experience timeline

Skills – Animated bars for technical expertise

Contact Section – Demo contact form with localStorage

Footer – Social links & copyright

✔ Interactions & Effects

Scroll reveal animations

Glassmorphism design

Project filter buttons

Preview modal for projects

Glow theme toggle

Demo contact form confirmation

🛠️ Technologies Used
Tech	Description
HTML	Structure of the page
TailwindCSS	Styling & layout framework
JavaScript (Vanilla)	Logic, animation, filters, modal
CSS Variables	Theming (glow, background, gradients)
LocalStorage	For demo contact messages
📁 Project Structure
📦 Portfolio Website
└── index.html


Everything is contained inside index.html, including
HTML structure • TailwindCSS styling • Custom CSS • JavaScript logic.

🖥️ How to Run This Project
1. Download or clone the repository
git clone https://github.com/kr1stn3/myportforlioweb.io

2. Open the project

Just open index.html in any browser:

Chrome

Firefox

Edge

Safari

3. No server needed

Tailwind CSS is loaded via CDN, so everything works instantly.

🔧 Customization Guide

You can easily personalize the site:

✏️ Change Name & Role

Inside the header and hero section:

Kristine Ariola — Software Engineer

🎨 Update Colors

Modify the CSS variables inside <style>:

:root {
  --bg: #0b1020;
  --primary: #7c8cff;
  --accent: #66e4c6;
}

🖼️ Add New Projects

Duplicate any .project-card block under the Work Section.

📬 Connect Contact Form

Replace the demo functionality with an actual backend/email service like:

EmailJS

Firebase

PHP

Node.js

📸 Screenshot Preview (optional for GitHub)

You may add an image here:

![Portfolio Preview](preview.png)
