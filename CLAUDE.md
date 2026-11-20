# stunningdigital.com: brief for Claude Code

This folder is the finished Stunning Digital website, built and tested in a Claude chat on 20 Nov 2026.
Plain HTML and CSS. No framework, no build step, no package installs. Do not add any.

## Your job in this session

1. This folder should live at `D:\projects\stunningdigital`. If it isn't there yet, move it there.
2. Make it a git repo and push it to a new **public** GitHub repo called `stunningdigital` on the CapricaTix account.
   Public is required: GitHub Pages on a free account only works from public repos. Everything in here is meant to be public.
   - `git init`, commit everything, then `gh repo create CapricaTix/stunningdigital --public --source . --push` (or the GitHub website if `gh` isn't set up).
3. Switch on GitHub Pages: Settings > Pages > Deploy from a branch > `main` / root. Check the current GitHub docs if the menus differ.
4. Wait for it to publish, then give Tix the test address (likely `https://capricatix.github.io/stunningdigital/`).
5. Test on that address, and report what you actually see:
   - Phone width and desktop, light and dark mode (dark mode follows the system setting).
   - Every link and every `mailto:` button opens an email to hello@stunningdigital.com.
   - The favicon shows in the browser tab.
   - The 404 page: visit a made-up address.
   Note: on the project address, the 404 page's `/styles.css` and `/favicon.svg` links point to the domain root, so it will look unstyled until the custom domain is switched on. That's expected, not a bug to fix.

## Do NOT do yet

- Do not add a `CNAME` file or set a custom domain in Pages. That's the final switch-over, after:
  - Tix has control of the stunningdigital.com DNS.
  - hello@stunningdigital.com exists and a test email from outside actually arrives.
- Do not touch the live Bolt site. It stays up until this one is proven.

## House rules for any edits

- Plain, warm British English. No em dashes anywhere.
- Contact address on the site is hello@stunningdigital.com (never tix@).
- The mark is the outline circle with the wire s. Its versions for dark, orange, busy and one-colour backgrounds are fixed: don't invent new ones.
- Don't say how beautistation is built.
- Test before it counts: check changes on the test address before calling anything done.
