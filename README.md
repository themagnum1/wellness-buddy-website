# Wellness Buddy Website

**Domain:** wellnessbuddyltd.africa  
**Staging:** Deploy to Vercel (instructions below)

## Files
- `index.html` — Homepage
- `about.html` — About Us, Mission/Vision, Core Values, Sustainability
- `solutions.html` — All Products & Services
- `thrive-desk.html` — The Thrive Desk Employee Navigation Program
- `shop.html` — E-Commerce Shop
- `partners.html` — Partners (JDPC)
- `podcast.html` — Lead and Live Well Podcast
- `contact.html` — Contact Page
- `vercel.json` — Vercel deployment config

## Deploy to Vercel (3 ways)

### Option A — Drag & Drop (Easiest, no account needed)
1. Go to https://vercel.com/new
2. Sign up free with Google or GitHub
3. Click **"Deploy a folder"** or drag this entire folder onto the page
4. Vercel gives you a live URL in under 60 seconds
5. Share that URL with the CEO to review

### Option B — Vercel CLI
```bash
npm install -g vercel
cd wellness_buddy_site
vercel
```
Follow the prompts. You'll get a URL like:  
`https://wellness-buddy-xyz.vercel.app`

### Option C — GitHub + Vercel (Best for ongoing updates)
1. Create a free GitHub account at https://github.com
2. Create a new repository called `wellness-buddy-website`
3. Upload all files in this folder to that repo
4. Go to https://vercel.com → Import Git Repository
5. Connect your GitHub repo → Deploy
6. Every time you push changes to GitHub, Vercel auto-deploys

## Production Hosting (Go Live)
When ready to go live on wellnessbuddyltd.africa:
1. Purchase hosting on Truehost.com.ng
2. Change nameservers in Go54 dashboard to Truehost's
3. Upload these files via Truehost cPanel File Manager
4. Activate free SSL certificate in cPanel

## Notes
- All logos are embedded as base64 — no external files needed
- Year in footer auto-updates via JavaScript every January
- Emails: all end with @wellnessbuddyltd.africa
- Social media: @wellnessbuddy.africa (YouTube, Instagram, Facebook)
- PODCAST.docx content has been fully integrated into podcast.html
