# Sparkhauz Website

Static single-page site. No build step required.

## Deploy to Vercel

**Option A — Vercel CLI (fastest)**
1. Install the CLI if you don't have it: `npm i -g vercel`
2. From inside this folder, run: `vercel`
3. Follow the prompts (link/create a project), then `vercel --prod` to go live.

**Option B — GitHub + Vercel dashboard (same flow you used for Food Express)**
1. Create a new GitHub repo and push this folder:
   ```
   git init
   git add .
   git commit -m "Sparkhauz site"
   git branch -M main
   git remote add origin <your-repo-url>
   git push -u origin main
   ```
2. Go to vercel.com → New Project → Import the repo.
3. Framework preset: "Other" (it's plain HTML, no build command needed).
4. Deploy.

## Before going live
- [ ] Replace hero photo with a real Sparkhauz photo (currently a free-license Unsplash stock photo)
- [ ] Swap in real logo + brand colors (placeholder teal/lime palette is set via CSS variables at the top of index.html)
- [ ] Replace the 20 placeholder testimonials in the `TESTIMONIALS` array near the bottom of index.html with real client reviews
- [ ] Double-check WhatsApp link, email, and phone number are correct
- [ ] Consider a custom domain (e.g. sparkhauz.com) in Vercel project settings
