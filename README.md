# Ansa Yasir — UGC Portfolio Site

A lavender-themed, mobile-friendly one-page site: Hero, Why Choose Me, Brands, Results, Reviews, Contact.

## Deploy to Vercel (no build needed — it's plain HTML/CSS/JS)

**Option A — from the Vercel dashboard (easiest, no terminal):**
1. Go to vercel.com and sign in (or create a free account).
2. Click "Add New" → "Project" → "Deploy" (or drag-and-drop this whole folder onto the Vercel dashboard).
3. When asked for a framework preset, choose "Other" — no build command or output directory needed.
4. Click Deploy. You'll get a live `.vercel.app` link in under a minute.

**Option B — from the terminal, using the Vercel CLI:**
```bash
npm i -g vercel
cd ugc-site
vercel
```
Follow the prompts (link/create a project), then run `vercel --prod` to push it live.

**Option C — connect a GitHub repo:**
1. Push this folder to a new GitHub repository.
2. In Vercel, "Add New" → "Project" → import that repo → Deploy.
3. Every future push to `main` auto-deploys.

## What to personalize before launch
- **Stats & numbers** (hero stat card, "Views across my platforms"): currently placeholders (60+ collabs, 2M+ views, etc.) — swap in real numbers in `index.html`.
- **Reviews**: three sample testimonials are placeholders — replace with real client quotes when you have them.
- **Hand photo**: swap `assets/hand-hero.jpeg` for any photo — just keep the same filename, or update the `src` in `index.html`.
- **Contact form**: it opens the visitor's email app with a pre-filled message (no backend/server needed, works out of the box on Vercel). If you'd rather have submissions land in an inbox automatically, this can be upgraded to a service like Formspree.

## File structure
```
ugc-site/
├── index.html      → all page content & structure
├── styles.css       → lavender design system + responsive rules
├── script.js        → nav menu, scroll animations, contact form
└── assets/
    └── hand-hero.jpeg
```
