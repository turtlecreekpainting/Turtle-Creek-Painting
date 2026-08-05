# Turtle Creek Painting — Website

A single-page, luxury/modern marketing site for Turtle Creek Painting (Lebanon, OH), built with plain HTML/CSS/JS — no build step required.

## Files
- `index.html` — page structure and content
- `style.css` — design system (colors, type, layout, animation)
- `script.js` — sticky header, mobile nav, FAQ accordion, custom red-dot cursor

## Run locally
Just open `index.html` in a browser, or serve it:
```bash
npx serve .
```

## Deploy on GitHub Pages
1. Create a new GitHub repository (e.g. `turtle-creek-painting-site`).
2. Push these three files to the repo root:
   ```bash
   git init
   git add .
   git commit -m "Initial luxury site build"
   git branch -M main
   git remote add origin https://github.com/<your-username>/turtle-creek-painting-site.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Select branch `main`, folder `/root`, then **Save**.
6. Your site will publish at:
   `https://<your-username>.github.io/turtle-creek-painting-site/`

## Notes
- All outbound links (Services, About Us, Service Area, References, phone number tel: link, and email mailto:) point to the live Turtle Creek Painting pages/contact details as provided.
- The custom red-dot cursor only activates on devices with a mouse/trackpad (`pointer: fine`) and respects the OS "reduce motion" setting — on touch devices the normal cursor/tap behavior is used.
- The Google Map embed is used in both the Contact section and the footer, exactly as provided.
- Images are currently linked directly from the live `turtlecreekpainting.com` media library. For full independence from that site, download the images and place them in an `/images` folder, then update the `src` paths in `index.html`.
