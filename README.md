# TEJX.1 - Website Project (Clean & Modular)

This folder contains the complete, standalone website with **external CSS stylesheets**, all HTML pages, and all images/icons.

## 📁 Folder Structure

```
texj.1/
├── index.html               # Main homepage (links to assets/css/style.css)
├── blog.html                # Blog & guides page (links to assets/css/style.css)
├── style.css                # Standalone root stylesheet
├── css/                     # Direct CSS folder
│   └── style.css
├── assets/
│   ├── css/                 # Production stylesheets
│   │   ├── style.css        # Unified master stylesheet
│   │   ├── index.css        # Homepage stylesheet
│   │   └── blog.css         # Blog stylesheet
│   ├── images/              # All 19 high-resolution images & logos
│   └── icons/               # Standalone Lucide SVG & social icons
└── README.md                # Project documentation
```

## ✨ What was done:
1. **Extracted CSS**: Removed all inline `<style>` tags from both `index.html` and `blog.html`.
2. **Modular Stylesheet**: Created `assets/css/style.css` (and root `style.css`), containing all color tokens, navigation blur, hero styles, animations, glowing social buttons, cards, and responsive media queries.
3. **Assets Included**: Bundled all 19 original images and 32 SVG icons so the project is 100% self-contained and ready to deploy.
