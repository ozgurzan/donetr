# donetr.com — new static website

Single-file website (`index.html`) for Done Iletisim Bilgi Sistemleri A.S.
No frameworks, no build step, no dependencies — works on any free static host.

## How to host for free (recommended: Cloudflare Pages)

### Option A — Cloudflare Pages (recommended)
1. Sign up / log in at https://pages.cloudflare.com (free plan).
2. Create a project → "Direct Upload" → drag & drop this folder (just `index.html` is enough).
3. In the project settings → **Custom domains** → add `www.donetr.com` and `donetr.com`.
4. At your domain registrar, update DNS as Cloudflare instructs (a CNAME to your `*.pages.dev` URL).
5. Done — free hosting, free SSL, global CDN.

### Option B — GitHub Pages
1. Create a public repo (e.g. `donetr-site`), upload `index.html`.
2. Repo Settings → Pages → deploy from `main` branch.
3. Settings → Pages → Custom domain → `www.donetr.com`, then add a CNAME
   record at your registrar pointing `www` to `<username>.github.io`.

### Option C — Netlify
1. https://app.netlify.com → "Add new site" → "Deploy manually" → drag & drop the folder.
2. Site settings → Domain management → add `donetr.com` and follow the DNS instructions.

## After going live
- Cancel the Strikingly subscription **after** DNS has switched over and the new site is confirmed live on donetr.com.
- To update content later, just edit `index.html` and re-upload (or push to the repo).
