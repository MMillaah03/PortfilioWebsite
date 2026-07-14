# [Mike Miller] — Personal Portfolio Website

A clean, minimalist personal portfolio built with HTML & CSS that is fully responsive across desktop, tablet, and mobile.

## File Structure

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


## Setting Up the Contact Form (Formspree)
The contact form uses [Formspree]

1. In `pages/contact.html`, replace:
   ```
   action= https://formspree.io/f/meeyqeol
   ```

## Customized Colors
All colors are CSS variables in `css/style.css`:
```css
:root {
  --navy:    #000060;   /* Primary dark navy */
  --accent:  #2563eb;   /* Blue accent */
  --sky:     #4a6fa5;   /* Mid blue */
  /* ... */
}
```

## Responsive Breakpoints

| Breakpoint | Target |
|---|---|
| `> 960px` | Desktop / Laptop |
| `≤ 768px` | Tablet |
| `≤ 480px` | Mobile |

---