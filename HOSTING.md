# How to publish this site

## Option A: GitHub Pages (free, easiest)
1. Create a free account at github.com, then click New repository. Name it e.g. `abandoned-not-forgotten`, set Public, click Create.
2. Click "uploading an existing file". Drag in every file from this folder (index.html, README.md, LICENSE, CREDITS.md, HOSTING.md, SUBMISSION.md, .gitignore, .nojekyll). Click Commit changes.
3. Go to Settings > Pages. Under Build and deployment choose "Deploy from a branch", branch `main`, folder `/ (root)`, click Save.
4. After 1-2 minutes your site is live at https://YOUR-USERNAME.github.io/abandoned-not-forgotten/

## Option B: GoDaddy hosting plan (cPanel)
1. Sign in at godaddy.com > My Products > Web Hosting > Manage.
2. Open cPanel Admin > File Manager > the `public_html` folder.
3. Delete or rename any default page (index.html, "coming soon" or default.php).
4. Click Upload and add `index.html` (5 MB is fine).
5. Visit your domain. Turn on SSL (HTTPS) from the SSL / AutoSSL section if it is not on.

## Option C: GoDaddy domain pointing to GitHub Pages
1. Finish Option A first.
2. GoDaddy > My Products > Domains > your domain > DNS.
3. Delete any "parked" A record on `@`. Add four A records on `@` pointing to:
   185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
4. Add a CNAME record: name `www`, value `YOUR-USERNAME.github.io`.
5. In GitHub: Settings > Pages > Custom domain, type your domain, Save. When the DNS check passes (up to 24-48 hours), tick "Enforce HTTPS".

GoDaddy's screens change from time to time; use the same ideas if labels differ.
