# stunningdigital.com: brief for Claude Code

This folder is the Stunning Digital website, live at https://stunningdigital.com.
Plain HTML and CSS. No framework, no build step, no package installs. Do not add any.

## Where it lives

- Local folder: `D:\projects\stunningdigital`.
- GitHub: the public repo `CapricaTix/stunningdigital`, branch `main`.
- Hosting: Netlify, project `stunningdigital`. It deploys from `main` on every push, with the repo root as the publish directory and no build command.
- Addresses: https://stunningdigital.com is the main one. The www address and plain http redirect to it. Netlify also serves the same site at https://stunningdigital.netlify.app.
- DNS points at Netlify, and Netlify looks after the HTTPS certificate.

## Previous host

- GitHub Pages was the previous host. Its settings and the `CNAME` file are left as they are for now. Don't change or remove them unless Tix asks.

## Testing a change

Push to `main`, wait for Netlify to deploy, then check on the live address or the netlify.app address and report what you actually see:

- Phone width (375px and 320px) and desktop, light and dark mode (dark mode follows the system setting).
- Every `mailto:` button opens an email to hello@stunningdigital.com.
- The favicon shows in the browser tab.
- The 404 page: visit a made-up address.

For anything risky, test locally first with a simple local server before pushing, because a push to `main` goes live.

## House rules for any edits

- Plain, warm British English. No em dashes anywhere.
- Contact address on the site is hello@stunningdigital.com (never tix@).
- The mark is the outline circle with the wire s. Its versions for dark, orange, busy and one-colour backgrounds are fixed: don't invent new ones.
- Don't say how beautistation is built.
- Test before it counts: check changes on the live or netlify.app address before calling anything done.
