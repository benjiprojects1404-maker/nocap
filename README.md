# $NOCAP site

One file, self-contained, no build step. This is everything you need to deploy it.

- `index.html` — the whole site: HTML, CSS, and JS all inlined. Nothing else to install.

## Deploy (any of these)

**Vercel:** vercel.com → Add New → Project → drag `index.html` in.

**Cloudflare Pages:** dashboard → Workers & Pages → Create → Pages → Upload assets → drag `index.html` in.

**GitHub Pages:** new repo → upload `index.html` at the root → Settings → Pages → source = main branch, root folder.

Any of these give you a free URL immediately. Rename nothing — `index.html` is already the correct filename for all three to serve it as the homepage.

## Note

This file was pulled from the larger NoCap - Meme project folder (contracts, deploy scripts, etc.) — those aren't needed for hosting the site and can stay wherever they already are. This folder is just the one piece relevant to putting the page online.
