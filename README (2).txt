# Personal Portfolio Website

## Preview
Open `index.html` in a modern browser. Keep the `images` folder beside it.

## Customize
1. Update the displayed name in `index.html` in both language settings.
2. Update the contact email text and `mailto:` link in `index.html`.
3. Replace `YOUR CITY` with your city, or remove that line.
4. Project descriptions and labels are in the `projects` array near the bottom of `index.html`.
5. Replace any image in `images` with your updated image, keeping the same filename.

## Files
- `index.html` — complete HTML, CSS and JavaScript
- `images/` — the four supplied project images

No build tools, libraries or installation are required.

## Decorative interactions
The project cards include small animated SVG doodles. Hover over them to pause/transform them; move the pointer over a project image to gently nudge the doodles.

## Language switcher
The top-right EN / 中文 control switches the whole site between English and Chinese, including project detail popups. The choice is remembered in the browser.

## Publish to the internet (free, no build step)
This is a plain static site with relative paths, so it works on any static host. Keep `index.html` and the `images` folder together.

Option A — Netlify Drop (fastest)
1. Zip the folder containing `index.html` and `images`.
2. Open https://app.netlify.com/drop and drag the ZIP in.
3. You get a public URL immediately (e.g. https://random-name.netlify.app). Rename it in Netlify site settings.

Option B — GitHub Pages
1. Create a GitHub repository and upload `index.html` and `images`.
2. Repo Settings → Pages → Source: "Deploy from a branch" → `main` / `/root` → Save.
3. Your site is live at `https://<username>.github.io/<repo-name>/`.

Option C — Vercel Drop
1. Sign in to a free Vercel account so you can keep the deployment and manage the project.
2. Open https://vercel.com/drop.
3. Drag the project folder containing `index.html` and `images/` onto the page, or choose the folder to upload.
4. Choose your Vercel team, enter a project name, and select Deploy.
5. When deployment finishes, open the generated public HTTPS URL and test the page and project popups.

If you deploy without signing in, the static deployment is temporary and will expire unless you claim it before the countdown ends. Vercel Drop does not connect the project to Git; upload the folder again to publish later changes, or connect a Git repository for automatic deployments.

To use your own domain, buy one from any registrar and add the CNAME/A record provided by your host.
