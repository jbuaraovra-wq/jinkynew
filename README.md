# Jinky Buarao Portfolio Website

A responsive, static portfolio website designed for Vercel using your requested palette:
- Blue: `#7398c6`
- Pale blue: `#e9f0f6`
- Charcoal: `#282b38`
- White: `#ffffff`
- Warm cream: `#ffebcb`

Typography uses **Manrope** for strong headlines and **DM Sans** for readable body text.

## Before you publish

1. Open `public/images/`.
2. Your portrait is already included at `public/images/jinky-profile.jpg`.
   - Use a portrait-oriented image for the best result.
   - The website includes a temporary visual placeholder until you add the photo.
3. In `index.html`, review the three project cards:
   - Replace sample links with your exact Facebook/TikTok/Instagram/project URLs.
   - Update project descriptions and labels so they accurately represent your work.
   - The card artwork is CSS illustration artwork, not screenshots of your actual projects.
4. Check the contact email and social links.

The original Canva portfolio link is included as `https://canva.link/mklm3iffowcquw8`. If your Canva site uses a different public URL, update that link in `index.html`.

## Deploy to Vercel

**Option A — Upload with GitHub (recommended)**
1. Create a new repository on GitHub.
2. Upload all files and folders from this project (keep `index.html`, `styles.css`, `script.js`, `vercel.json`, and `public/` at the repository root).
3. Sign in to Vercel and choose **Add New → Project**.
4. Import the GitHub repository.
5. Vercel should detect this as a static site. If prompted, leave the build command blank and set the output directory to `.` (the project root).
6. Click **Deploy**.

**Option B — Vercel CLI**
1. Install Node.js if you don't already have it.
2. In this folder, run `npx vercel` and follow the prompts.
3. Run `npx vercel --prod` to publish the production deployment.

## Website sections
- Hero / introduction
- About
- Services
- Project cards
- Tools and skills
- Email contact CTA

## Important note about the image
Your uploaded portrait is included as `public/images/jinky-profile.jpg`. Your email is linked using `mailto:` so visitors can click to contact you.
