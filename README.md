# Chetan & Usha's Gruhapravesha

Interactive housewarming invitation for Sunday, 22 November 2026.
Live at **https://shashankabcbuilds.in**

## Files

| File | What it is |
|---|---|
| `index.html` | The invitation page (door, cards, scratch card, countdown, venue) |
| `bg2.png` | Background image |
| `music.mp3` | Background music |
| `preview.jpg` | Picture shown when the link is shared on WhatsApp |
| `CNAME` | Tells GitHub Pages to serve the site on shashankabcbuilds.in |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publish on GitHub Pages

1. Create a new public repository on GitHub, for example `housewarming`.
2. Upload every file in this folder to the repository (Add file → Upload files). Include `CNAME` and `.nojekyll`.
3. In the repository, open **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. Under **Custom domain**, enter `shashankabcbuilds.in` and save.

## Point the domain at GitHub

At the company where you bought shashankabcbuilds.in, open the DNS settings and add:

| Type | Name / Host | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | `<your-github-username>.github.io` |

Remove any other A records on `@` that point somewhere else.

DNS changes can take up to 24 hours. Once the domain shows as verified in Settings → Pages, tick **Enforce HTTPS**.

## Personal links

Add a guest's name after `#` to greet them by name, for example:
`https://shashankabcbuilds.in/#Ramesh-Uncle`
