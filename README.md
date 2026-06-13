# cicerone_web

Landing page for **Cicerone**, the AI-powered travel planning app.

Static site (HTML/CSS/JS, no build step) inspired by the layout of
[free-now.com/es](https://www.free-now.com/es/), adapted to Cicerone's
branding and content.

## Structure

```
index.html      # Page markup
css/style.css   # Styles
js/main.js      # Mobile nav toggle
assets/images/  # App icon / logo
```

## Local preview

Open `index.html` directly in a browser, or serve it locally:

```bash
npx serve .
```

## Deploy to Vercel

No build configuration needed — Vercel will detect and deploy this as a
static site.

```bash
npx vercel        # preview deploy
npx vercel --prod # production deploy
```

Or import the repo from the Vercel dashboard and deploy with default
settings (Framework Preset: "Other").
