# [Your Name] — Personal Portfolio Website

A clean, minimalist personal portfolio built with **pure HTML & CSS**, fully responsive across desktop, tablet, and mobile. Hosted on GitHub Pages.

---

## 📁 File Structure

```
portfolio/
├── index.html              ← Landing / Home page
├── css/
│   ├── style.css           ← Global design system (nav, footer, shared)
│   ├── home.css            ← Home page styles
│   ├── bio.css             ← Bio page styles
│   ├── skills.css          ← Skills page styles
│   ├── experiences.css     ← Experiences page styles
│   └── contact.css         ← Contact page styles
├── pages/
│   ├── bio.html            ← Biography page
│   ├── skills.html         ← Skills & Academic Achievements
│   ├── experiences.html    ← Travel & World Experiences
│   └── contact.html        ← Contact form + Instagram link
└── assets/                 ← Add your photos here
    └── your-photo.jpg      ← Replace placeholder avatar
```

---

## 🚀 Setting Up GitHub Pages

1. Push all files to your GitHub repo (`main` branch)
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder `/`
4. Save — your site will be live at `https://[username].github.io/[repo-name]/`

---

## ✏️ Personalizing Your Site

Search for `[Your Name]`, `[Your University]`, `[yourusername]`, etc. and replace with your real info. Key spots:

| Placeholder | Where to update |
|---|---|
| `[Your Name]` | All HTML files — nav logo, footer, meta tags |
| `[Your Full Name]` | `index.html` hero section |
| `[Your University]` | `bio.html`, `skills.html` |
| `[yourusername]` | All Instagram links in `bio.html` & `contact.html` |
| `youremail@example.com` | `contact.html` |
| `YOUR_FORM_ID` | `contact.html` form action — see Formspree setup below |

### Adding Your Photo
Replace the avatar placeholder in `index.html` and `bio.html`:
```html
<!-- Remove this: -->
<span class="avatar-initials">[YN]</span>

<!-- Add this: -->
<img src="assets/your-photo.jpg" alt="[Your Name]" />
```

---

## 📬 Setting Up the Contact Form (Formspree)

The contact form uses [Formspree](https://formspree.io) — free, no server required.

1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form → copy your Form ID (e.g. `xpzvwkqr`)
3. In `pages/contact.html`, replace:
   ```
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
   with your actual form ID.

---

## 🎨 Customizing Colors

All colors are CSS variables in `css/style.css`:
```css
:root {
  --navy:    #000060;   /* Primary dark navy */
  --accent:  #2563eb;   /* Blue accent */
  --sky:     #4a6fa5;   /* Mid blue */
  /* ... */
}
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Target |
|---|---|
| `> 960px` | Desktop / Laptop |
| `≤ 768px` | Tablet |
| `≤ 480px` | Mobile |

---

Built with ❤️ using HTML & CSS · No frameworks · No dependencies
