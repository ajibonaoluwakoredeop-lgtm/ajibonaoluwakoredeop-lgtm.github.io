# Oluwakorede Ajibona — Academic Website

## Files
- `index.html` — the complete responsive one-page website.
- `portrait.jpg` — add your professional photograph using this exact filename.
- `cv.pdf` — add your academic CV using this exact filename.
- `CNAME` — add your purchased custom domain here after choosing it.

## Before publishing
1. The supplied KU email address has been added. Confirm it is the preferred public contact address.
2. Replace the ORCID, Google Scholar, and LinkedIn links with your personal profile URLs.
3. Add your photo as `portrait.jpg`. In `index.html`, replace the placeholder `<span>` inside `.portrait` with:
   `<img src="portrait.jpg" alt="Portrait of Oluwakorede Ajibona">`
4. Your supplied CV has been formatted and included as `cv.pdf`.
5. Check all biography, affiliation, research and project wording for accuracy.
6. Add verified publications and presentations when ready.

## Fast publishing with GitHub Pages
1. Sign in to https://github.com/ or create an account.
2. Create a **public** repository named exactly `YOUR-GITHUB-USERNAME.github.io`.
3. Upload `index.html`, `portrait.jpg`, and `cv.pdf` to the repository's root.
4. Open repository **Settings → Pages**. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Your initial site will be at `https://YOUR-GITHUB-USERNAME.github.io/`.

## Connect your custom domain
1. Buy a domain from a registrar. Check availability before choosing a name; `koredeajibona.com` is only a suggested name, not a verified available domain.
2. In GitHub repository **Settings → Pages → Custom domain**, enter your purchased domain and Save.
3. At your domain registrar, configure DNS. For a root/apex domain, GitHub's current recommended A records are:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
4. For `www`, add a CNAME record pointing `www` to `YOUR-GITHUB-USERNAME.github.io`.
5. Wait for DNS to propagate, then enable **Enforce HTTPS** in GitHub Pages settings.

Use GitHub's current documentation for exact steps:
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/securing-your-github-pages-site-with-https

Note: GitHub Pages sites are public. Do not upload private or sensitive documents.
