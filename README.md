# cancan_web

This is a static site for cancanindia.com.

How to push to GitHub and deploy to Cloudflare Pages:

1. Create a GitHub repo (empty) named e.g. `cancan_web`.
2. On your machine:

```bash
cd "/Users/creativecrossbreed/Desktop/STUDIES/HTML | CSS | JS/cancan_web"
git remote add origin git@github.com:YOUR_USER/cancan_web.git
git branch -M main
git push -u origin main
```

3. In Cloudflare dashboard → Pages → Create project → Connect your GitHub repo → set build settings to no build command and output directory `/` → Deploy.
4. In Cloudflare Pages project → Custom domains → Add `cancanindia.com` → follow verification.

Notes:
- `CNAME` file already added with `cancanindia.com` for Pages/GitHub Pages compatibility.
- If you prefer not to use Git, you can drag-and-drop the site to Netlify instead.
