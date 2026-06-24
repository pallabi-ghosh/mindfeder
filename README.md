# Mindfeder — Mental Health Space

Responsive site built with Astro + Tailwind. Six pages: Home, About, Services, Experiences, Shop, Contact.

## Run locally
    npm install
    npm run dev          # http://localhost:4321

## Deploy to Netlify
1. Push this folder to a GitHub repo.
2. On netlify.com: "Add new site" → "Import an existing project" → pick the repo.
3. Build settings are auto-detected from netlify.toml (build: `npm run build`, publish: `dist`).
4. Deploy. Netlify gives you a live URL like https://mindfeder.netlify.app

## Contact form
The contact form uses Netlify Forms (data-netlify="true"). Submissions appear in the
Netlify dashboard under "Forms" once deployed. No backend needed.

## Still to wire up (needs Kumarica's input)
- Real images: hero, About photo, journal cover (placeholders in place now)
- Shop "Buy Now": replace the placeholder href with a real Razorpay payment link
- Booking: embed Cal.com / Calendly on a "Book a Session" page
