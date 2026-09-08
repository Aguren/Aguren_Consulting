# Fractional IT Director Consulting Site

This is a static one-page site designed for GitHub Pages.

## Replace these placeholders before publishing

Search the project for:

- `YOUR NAME`
- `YN` — replace with your initials
- `YOUR_EMAIL`
- `YOUR_LINKEDIN_URL`

You may also want to update:
- prices
- service wording
- target company size
- page title / meta description

## GitHub Pages deployment

1. Create a new GitHub repository.
2. Upload `index.html`, `styles.css`, and `script.js` to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save.
7. GitHub will provide a `github.io` address.

## Custom domain

In **Settings → Pages**, enter your custom domain.

For an apex/root domain such as `yourname.com`, GitHub currently documents these A records:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

For `www`, create a CNAME pointing to:

`YOUR-GITHUB-USERNAME.github.io`

Check GitHub's current Pages documentation before changing DNS, since infrastructure details can change.

After DNS resolves, enable **Enforce HTTPS** in GitHub Pages.

## Email

Website DNS records can coexist with your email records. Your MX/SPF/DKIM/DMARC records remain separate from the GitHub Pages A/CNAME records.

## Files

- `index.html` — all page content
- `styles.css` — layout and visual design
- `script.js` — mobile menu + automatic copyright year
