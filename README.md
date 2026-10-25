# swipefold.app website

The public website for Swipefold: `index.html` (home) and `privacy.html` (privacy policy, linked from the app stores).

To put it live with GitHub Pages:
1. Create a new **public** repository called `swipefold-site` and copy everything in this folder into it.
2. In that repository: Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
3. The `CNAME` file already says `swipefold.app`. In GoDaddy's DNS for swipefold.app, add four **A** records for `@` pointing to 185.199.108.153, 185.199.109.153, 185.199.110.153 and 185.199.111.153, and a **CNAME** record for `www` pointing to `dash-demberel.github.io`.
4. Back in Settings → Pages, tick **Enforce HTTPS** once GitHub shows the certificate is ready.
