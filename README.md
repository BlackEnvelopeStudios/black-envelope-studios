# Black Envelope Studios — Website v1

A static, hand-built site for **Black Envelope Studios**.

## What's included

- `index.html` — page content and structure
- `styles.css` — all visual styling and responsive layouts
- `script.js` — subtle reveal animations, navigation behavior, and automatic copyright year
- `assets/black-envelope-studios-logo.png` — the chosen studio logo

There are **no frameworks, databases, build tools, or paid dependencies**.

## Preview it locally

The simplest method:

1. Unzip the folder.
2. Open `index.html` in Firefox, Chrome, Edge, or Safari.

For a more accurate local preview, run a tiny local web server from the project directory:

```bash
python -m http.server 8000
```

Then visit:

`http://localhost:8000`

## Going live later

This site can be hosted for $0/month on services such as:

- GitHub Pages
- Cloudflare Pages
- Netlify

Your Porkbun domain can point to the website host while Proton continues handling email.  
**Do not delete Proton MX/SPF/DKIM/DMARC records when connecting the website.**

## Current site content

- Studio introduction
- First game: *The Veiled Invitation*
- Inquiries email
- Support email
- Responsive desktop/mobile layout
- Dark Black Envelope Studios visual identity

## Easy edits

Open `index.html` in any text editor to change wording.

Open `styles.css` to change colors, spacing, typography, or layout.

The main color variables are at the top of `styles.css` under `:root`.
