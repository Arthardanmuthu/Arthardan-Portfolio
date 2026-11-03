# Arthardan Muthu G — Personal Portfolio

> A premium, recruiter-focused personal portfolio website built with pure HTML5, CSS3, and Vanilla JavaScript.

---

## 🚀 Live Preview

Open `index.html` in any modern browser to view the portfolio.

---

## 📁 Project Structure

```
Arthardan-Portfolio/
│
├── index.html              ← Main HTML (all sections)
├── css/
│   └── style.css           ← All styles, responsive design, animations
├── js/
│   └── script.js           ← Navbar, typed text, particles, scroll reveal
├── assets/
│   ├── images/             ← Profile photo (add as profile.jpg when ready)
│   └── icons/              ← Custom icons (if needed)
├── resume/
│   └── resume.pdf          ← ⚠️ Place your actual resume PDF here
└── README.md
```

---

## ✅ Features

| Feature | Status |
|---|---|
| Dark premium theme | ✅ |
| Responsive (375px / 768px / 1280px+) | ✅ |
| Sticky glassmorphism navbar | ✅ |
| Animated particle hero canvas | ✅ |
| Typed text animation | ✅ |
| Scroll reveal animations (IntersectionObserver) | ✅ |
| Active nav section highlighting | ✅ |
| Hamburger mobile menu | ✅ |
| Back-to-top button | ✅ |
| Dynamic copyright year | ✅ |
| Smooth scrolling | ✅ |
| SEO meta tags | ✅ |
| ARIA accessibility labels | ✅ |
| Reduced motion support | ✅ |
| No frameworks / no dependencies | ✅ |

---

## ⚙️ Setup Instructions

### 1. Add Your Resume
Place your resume PDF at:
```
resume/resume.pdf
```
The "Download Resume" button links directly to this file.

### 2. Update Social Links
Open `index.html` and find the **Contact section** (near the bottom).  
Replace the placeholder comments with your actual URLs:

```html
<!-- LinkedIn -->
<a href="https://linkedin.com/in/YOUR_USERNAME" ...>

<!-- LeetCode -->
<a href="https://leetcode.com/YOUR_USERNAME" ...>
```

### 3. Update Project GitHub Links
In the **Projects section**, each project card has a GitHub link currently pointing to your profile:
```html
<a href="https://github.com/Arthardanmuthu" ...>
```
Replace with the specific repository URL for each project when available.

### 4. Add Profile Photo (Optional)
Save your photo as `assets/images/profile.jpg` and add an `<img>` tag to the hero section if desired.

---

## 🎨 Customization

All design tokens (colors, spacing, fonts) are in `css/style.css` under `:root {}`:

```css
:root {
  --accent-blue:   #4F8EF7;
  --accent-violet: #8B5CF6;
  --bg-primary:    #080B12;
  /* ... */
}
```

---

## 🌐 Browser Support

| Browser | Support |
|---|---|
| Chrome 90+ | ✅ |
| Firefox 88+ | ✅ |
| Safari 14+ | ✅ |
| Edge 90+ | ✅ |

---

## 📝 Notes

- Resume PDF must be placed manually at `resume/resume.pdf`
- LinkedIn and LeetCode profile URLs should be added when available
- Individual project repository links should be updated as projects are published

---

*Designed & Built by **Arthardan Muthu G** — 2026*

