# Lily Austin Portfolio Website

An elegant one-page portfolio with scroll snap for Lily Austin, podcast producer.

## 📁 File Structure
```
lilyaustin-portfolio/
├── index.html                      # Complete website
├── pics/
│   └── lilyaustin_pic.JPG          # Profile photo
├── logos/                          # Podcast cover images
│   ├── fashion_logo.jpeg
│   ├── fd_logo.jpeg
│   ├── streetsinthesky_logo.png
│   └── groovymovies_logo.png
└── audio/                          # Audio highlight clips
    ├── MOF HIGHLIGHT.mp3
    ├── FD HIGHLIGHT 1.mp3
    ├── FDX HIGHLIGHT.mp3
    ├── STREETS IN THE SKY HIGHLIGHT.mp3
    └── GM HIGHLIGHT.mp3
```

## 🔐 Password Protection

The site is protected with a JavaScript password. To change the password:

1. Open `index.html`
2. Find this line near the top:
```javascript
   const SP = "LilyAustin2025";
```
3. Replace `"LilyAustin2025"` with your new password

## 🚀 Hosting Setup

The site is hosted on **Netlify** with the domain managed through **GoDaddy**.

### Updating the Site
1. Make changes to your local files
2. Test locally by opening `index.html` in your browser
3. Go to [Netlify](https://app.netlify.com) → your site → **Deploys**
4. Drag and drop the entire folder to upload

### DNS Settings (GoDaddy)
| Type | Name | Value |
|------|------|-------|
| A | @ | 75.2.60.5 |
| CNAME | www | capable-biscuit-c1eeb2.netlify.app |

## 📧 Contact Form (Formspree)

To configure the contact form:

1. Go to [Formspree](https://formspree.io) and log in
2. Create a new form or use an existing one
3. Copy the endpoint (e.g., `https://formspree.io/f/xyzabcde`)
4. In `index.html`, find this line:
```html
   <form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```
5. Replace `YOUR_FORM_ID` with your form ID
6. In Formspree settings, set destination email to `lilyaustinuk@gmail.com`

## 🎨 Colour Palette

Chosen to complement red hair and fair skin:

| Colour | Hex | Usage |
|--------|-----|-------|
| Blush | `#E8C4C4` | Accents, decorations |
| Peach | `#F2D7C9` | Borders, hover states |
| Sage | `#C5D5CB` | Tags, secondary elements |
| Cream | `#FDF8F4` | Main background |
| Terracotta | `#C9907D` | Primary accent, CTA |
| Warm Brown | `#8B6E61` | Headings, important text |

## ✏️ Customisations

### Editing Podcast Descriptions
Search for `<div class="work-description">` sections in the HTML to modify text.

### Changing the Profile Photo
Replace `pics/lilyaustin_pic.JPG` with a new image (square, at least 640x640px).

### Adjusting Photo Crop Position
Find in CSS:
```css
object-position: center 20%;
```
Change `20%` to adjust vertical position (0% = top, 50% = centre, 100% = bottom).

### Changing Colours
Colours are defined as CSS variables at the top of the file (`:root`). Modify them to change the entire palette.

## 📱 Responsive

The site is fully responsive and works on:
- Desktop
- Tablet
- Mobile

## 🔧 Technical Requirements

- Static file hosting (Netlify)
- No database required
- No external dependencies (except Google Fonts)

---

Made with ❤️ for Lily Austin