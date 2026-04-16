# Jordan Bennett — Customer Service Portfolio

A responsive personal portfolio website for a Customer Service Specialist, built for **ISMS 121 CA 2** using pure HTML5 and CSS3.

## 📁 Project Structure

```
portfolio/
├── index.html          # Home page
├── profile.html        # Profile / Skills page
├── projects.html       # Projects page (6 projects)
├── contact.html        # Contact Us page with form
├── styles.css          # Single external stylesheet
├── images/             # 6 project images
│   ├── project-1.jpg
│   ├── project-2.jpg
│   ├── project-3.jpg
│   ├── project-4.jpg
│   ├── project-5.jpg
│   └── project-6.jpg
└── README.md
```

## ✅ Requirements Checklist

- [x] 4 interconnected HTML pages (Home, Profile, Projects, Contact)
- [x] Consistent navigation bar across all pages
- [x] 6 project items with image, title, and description
- [x] External CSS stylesheet (`styles.css`)
- [x] CSS Flexbox & Grid for responsive layout
- [x] Fully responsive (mobile, tablet, desktop) via media queries
- [x] Hero section on Home page
- [x] Skills displayed with cards, progress bars, and tags
- [x] Styled HTML contact form (Name, Email, Subject, Message, Submit)
- [x] Semantic HTML5 (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- [x] Ready for GitHub Pages deployment

## 🚀 How to Deploy to GitHub Pages

1. **Create a new GitHub repository** (e.g., `portfolio`).
2. **Upload all the files** from this folder into the repository root (not inside a subfolder).
3. Go to your repo's **Settings → Pages**.
4. Under **"Branch"**, select `main` (or `master`) and folder `/ (root)`, then click **Save**.
5. Wait ~1 minute. Your site will be live at:
   `https://github.com/tofsjinadu/Customer_Service_Portfolio`

## 🎨 Design Notes

- **Typography**: Playfair Display (serif, headings) paired with Poppins (sans, body)
- **Color palette**: Deep navy `#0f2a44`, warm coral `#ff6f61`, cream background `#fdf6ee`
- **Layout**: CSS Flexbox for navigation, hero, and forms; CSS Grid for project cards
- **Responsiveness**: Media queries at `900px` (tablet) and `720px` (mobile)
- **Mobile menu**: Hamburger toggle reveals nav links on screens under 720px

## 📝 Customization

To make this yours:
1. Replace "Jordan Bennett" with your name in all HTML files and the footer
2. Update the bio, stats, skills, experience, and projects with your real content
3. Swap the 6 images in `/images/` with your own (keep the filenames)
4. Update the contact email, phone, and social links
