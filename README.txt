# VM Studio Website — Setup Notes

This is a single self-contained file: `index.html` (styles and scripts are inline, no build step needed).

## To go live, add these files in the SAME folder as index.html:

Images:
- studio.png        (hero background)
- logo.png           (VM Studio logo)
- visithiran.png     (About section photo)
- Img1.png, Img2.png, Img3.png, Img4.png   (Portfolio masonry grid)
- simg1.png – simg4.png   (Studio Photos gallery)
- limg1.png – limg4.png   (Live Performance gallery)

Audio:
- music.mp3          (sample track in the audio player)

Until these are added, the site shows clean placeholder boxes labeled with the expected filename — nothing looks broken, it just waits for real assets.

## Before publishing
Replace the placeholder domain `vmstudio.example.com` in:
- the `<link rel="canonical">` tag
- the Open Graph (`og:`) tags
- `sitemap.xml`

with your real domain once you have one, so SEO/social previews resolve correctly.

## Hosting
Drop the whole folder onto any static host — Netlify, Vercel, GitHub Pages, or your existing hosting via FTP. No server-side code, no dependencies to install.
