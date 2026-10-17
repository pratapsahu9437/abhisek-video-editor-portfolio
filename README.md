# Abhisek Sahu — Video Editor Portfolio

A responsive black-and-yellow portfolio website built with plain HTML, CSS, and JavaScript. It is suitable for GitHub Pages and custom domains.

## Files
- `index.html` — the complete website in one file.
- `README.md` — setup and publishing instructions.

## Before publishing
1. Open `index.html` in a text editor.
2. Find the `CONTACT` object near the bottom of the file.
3. Replace:
   - `YOUR_EMAIL@example.com` with your working email address.
   - `YOUR_WHATSAPP_NUMBER` with your country code and phone number, digits only (India: `91` + number).
   - `YOUR_INSTAGRAM` with your Instagram username, without `@`.
4. Update the portfolio project cards with real work. They are sample placeholders, not real client projects.
5. To link a project to a video, add an `<a>` link around the relevant project card or add a dedicated “Watch project” link using your YouTube/Vimeo/Drive link. For best performance, host videos externally and embed or link them rather than committing large video files to GitHub.

## Publish on GitHub Pages
1. Sign in to https://github.com and create a repository, e.g. `abhisek-video-editor-portfolio`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for the Pages deployment to complete. Your project URL will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/abhisek-video-editor-portfolio/`

## Add a custom domain
You need to own or register a domain name first (domain registration normally costs money).
1. In the repository, open **Settings → Pages → Custom domain**.
2. Enter your domain, e.g. `www.example.com`, and save. GitHub will add a `CNAME` file for you.
3. At your domain registrar, configure DNS:
   - For `www` subdomain: create a CNAME record with host `www` pointing to `YOUR-GITHUB-USERNAME.github.io`.
   - For an apex/root domain like `example.com`: add the four A records recommended in GitHub's current Pages documentation. GitHub's official guide has the current IP addresses.
   - If you want both root and `www`, configure both as GitHub recommends and choose the primary domain in Pages.
4. DNS can take time to update. After it resolves, enable **Enforce HTTPS** in Settings → Pages.
5. Keep the repository public unless your GitHub plan explicitly supports Pages publishing from a private repository.

Official documentation:
- https://docs.github.com/en/pages
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
