# stunningdigital.com

The Stunning Digital website. Plain HTML and CSS, no build step, hosted on Netlify from this repo.

## Files

- `index.html`: the homepage
- `styles.css`: all styles; dark mode follows the visitor's system setting
- `404.html`: page-not-found
- `assets/logos/`: product logos (frugl, matreez, beautistation), sized for the web
- `assets/people/`: Suzanne and Tix illustrations
- `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`: browser and phone icons
- `og-image.png`: the preview image shown when the link is shared

## Editing

Edit the HTML directly and push to `main`. Netlify republishes within a minute or two.

## Hosting

- Live at https://stunningdigital.com. The www address and plain http both redirect there.
- Netlify project `stunningdigital`, deploying from `main` with the repo root as the publish directory. There is no build command.
- Netlify also serves the site at https://stunningdigital.netlify.app, which is handy for checking a change.
- GitHub Pages was the previous host. The `CNAME` file is left over from that and Netlify ignores it.
