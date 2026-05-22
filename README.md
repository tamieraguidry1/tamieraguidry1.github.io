# Tamiera Guidry — UX Research Portfolio

A hand-coded portfolio site. No build process, no frameworks, no dependencies.
Just HTML, CSS, and two Google Fonts.

## Files

```
portfolio/
├── index.html                      Homepage with case study grid
├── about.html                      About page
├── case-host-enablement.html       Case study 1
├── case-host-risk.html             Case study 2
├── case-maintenance-tiers.html     Case study 3
├── styles.css                      All styling
├── Tamiera_Guidry_Resume.pdf       Resume (add this manually)
└── README.md                       This file
```

## How to view locally

Open `index.html` in any browser. That's it. No server needed.

## How to publish on GitHub Pages

### One-time setup

1. Go to **github.com** and sign in (create a free account if you don't have one)
2. Click the green **New** button to create a new repository
3. Name it **EXACTLY** `tamieraguidry1.github.io`
   - The username part must match your GitHub username
   - The `.github.io` part tells GitHub to host this as a Pages site
4. Set it to **Public**
5. Do NOT initialize with a README (we have one already)
6. Click **Create repository**

### Upload your files

Easiest way (no command line):

1. On your new empty repo page, click **uploading an existing file** (the link in the middle of the page)
2. Drag in all the files from this folder (index.html, about.html, the three case-*.html files, styles.css, your resume PDF, and this README.md)
3. At the bottom, type a commit message like "initial portfolio" and click **Commit changes**

That's it. Within 1–2 minutes, your site will be live at:

**https://tamieraguidry1.github.io**

### Updating the site later

To edit a file directly on GitHub:
1. Click the file in your repo
2. Click the pencil icon (top right)
3. Make changes
4. Scroll down, add a commit message, click **Commit changes**
5. Changes are live within a minute

For bigger edits, you can clone the repo locally with GitHub Desktop
(desktop.github.com) and edit files in any text editor.

## What to update before going live

1. **Add the resume PDF.** Save your resume as a PDF named exactly
   `Tamiera_Guidry_Resume.pdf` and drop it in the same folder.
   All the nav links point to this filename.

2. **Check the GitHub URL in the footer.** Both the footer and the About page
   link to `https://github.com/tamieraguidry1` — update if your GitHub username
   is different.

3. **Optional: add favicon.** Create a small `.ico` or `.png` icon and add this
   to the `<head>` of each HTML file:
   ```html
   <link rel="icon" type="image/png" href="favicon.png" />
   ```

## Editing case studies

Each case study is a single HTML file. The structure is the same in all three —
copy any of them as a template for the self-initiated usability study (case 04)
when that's ready.

The CSS is in `styles.css` and uses CSS custom properties at the top —
change colors, fonts, or max-width by editing the `:root` block.

## Design notes

- Fonts: Fraunces (display serif) + Inter (body sans) + JetBrains Mono (labels)
- Color palette: warm paper background, near-black ink, terracotta accent
- Mobile-responsive at 720px breakpoint
- No JavaScript except a small CSS animation on the homepage hero
- All animations are CSS-only (one staggered fade-in on hero load)

Built with care. Tweak anything.
