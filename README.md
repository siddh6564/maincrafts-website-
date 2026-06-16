# MainCrafts Technology – Full Stack Web Development Internship

## Task 1 & Task 2 – Multi-Page Responsive Website

![MainCrafts](https://img.shields.io/badge/MainCrafts-Technology-00c9a7?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📌 Project Overview

This project is a **modern, fully responsive multi-page website** built for the MainCrafts Technology Full Stack Web Development Internship.

- **Task 1** – Built a responsive landing page (Hero, Features, Services, Footer)
- **Task 2** – Extended to a 3-page website with form validation (Home, About, Contact)

---

## 📁 Project Structure

```
maincrafts-task2/
│
├── index.html       → Home Page (Hero + Features + Services)
├── about.html       → About Page (Mission, Values, Team)
├── contact.html     → Contact Page (Form + FAQ)
└── style.css        → Shared Stylesheet (all pages)
```

---

## 🚀 Features

### ✅ Task 1 Requirements
- [x] Header & Navigation with dropdown under "Services"
- [x] Hero Section with heading, tagline, CTA button, gradient background
- [x] Features Section with 4 cards and FontAwesome icons
- [x] Footer with Copyright, Privacy Policy, Terms, Contact
- [x] Google Fonts (Syne + DM Sans)
- [x] Gradients & hover effects
- [x] Fully responsive (desktop, tablet, mobile)

### ✅ Task 2 Requirements
- [x] 3 connected pages: Home, About, Contact
- [x] Responsive navbar across all pages with active link highlighting
- [x] Contact form with Name, Email, Subject, Message fields
- [x] JavaScript form validation (empty check + email format check)
- [x] Error messages shown inline (not just alerts)
- [x] CSS Grid & Flexbox for responsive layout
- [x] Mobile hamburger menu

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure & semantics |
| CSS3 | Styling, Flexbox, Grid, Animations |
| JavaScript (Vanilla) | Form validation, hamburger menu, FAQ accordion |
| Google Fonts | Syne (headings) + DM Sans (body) |
| Font Awesome 6 | Icons throughout the site |

---

## 📄 Pages Description

### 🏠 Home (`index.html`)
- Animated hero section with gradient mesh background
- Stats strip (200+ projects, 98% satisfaction, etc.)
- 4 feature cards (Fast, Responsive, Scalable, Secure)
- Services grid (Web Design, App Dev, Cloud, SEO)
- CTA band linking to Contact page

### 👥 About (`about.html`)
- Company mission & stats panel
- 4 core values (Craft, Transparency, Partnership, Growth)
- Team member cards (4 members)
- CTA section

### 📬 Contact (`contact.html`)
- Contact info cards (Email, Website, Response Time, Location)
- Social media links
- Contact form with full JS validation:
  - First name: required
  - Email: required + format validation
  - Subject: required
  - Message: required (min 10 characters)
- Loading spinner on submit
- Success screen after submission
- FAQ accordion section

---

## 🧪 Form Validation Logic

```javascript
// Checks performed on submit:
1. First Name  → must not be empty
2. Email       → must not be empty + must match email format regex
3. Subject     → must not be empty
4. Message     → must not be empty + minimum 10 characters

// Behavior:
- Fields highlight red with inline error messages
- Errors clear as user types (live feedback)
- Submit button shows loading spinner (1.5s)
- Success overlay replaces form on completion
- "Send Another Message" resets everything
```

---

## 🌐 How to Run Locally

1. **Download** all 4 files into the same folder
2. **Open** `index.html` in any browser (Chrome, Firefox, Edge)
3. All page links will work correctly

> ⚠️ All 4 files must be in the **same folder** for navigation to work.

---

## ☁️ Deploy to GitHub Pages (Free Hosting)

```bash
# Step 1: Create a new repository on github.com

# Step 2: Upload all 4 files to the repo root

# Step 3: Go to Settings → Pages → Source → main branch → Save

# Step 4: Your site is live at:
# https://yourusername.github.io/repository-name/
```

---

## ⚡ Deploy to Netlify (Fastest – No Account Needed)

1. Go to **[app.netlify.com/drop](https://app.netlify.com/drop)**
2. Drag and drop the project folder
3. Get a live URL instantly — no signup required

---

## 🎨 Design System

| Token | Value |
|---|---|
| Primary Color | `#00c9a7` (Teal) |
| Background | `#f0f4f8` (Mist) |
| Dark | `#0d0d0d` |
| Slate | `#1a1f2e` |
| Heading Font | Syne (800 weight) |
| Body Font | DM Sans (400/500) |
| Border Radius | 14px |

---

## 📚 Resources Used

- [Google Fonts](https://fonts.google.com) – Typography
- [Font Awesome](https://fontawesome.com) – Icons
- [Coolors](https://coolors.co) – Color palette
- [MDN Web Docs](https://developer.mozilla.org) – Reference
- [W3Schools](https://www.w3schools.com) – Form Validation

---

## 👨‍💻 Internship Info

- **Company:** MainCrafts Technology
- **Website:** [www.maincrafts.com](https://www.maincrafts.com)
- **Email:** hr@maincrafts.com
- **Program:** Full Stack Web Development Internship
- **Tasks Completed:** Task 1 ✅ | Task 2 ✅

---

© 2025 MainCrafts Technology. All rights reserved.
