# Signstimator Website

Simple informational landing page + Privacy Policy for the Signstimator mobile app.

## Files

- `index.html` — Main landing page
- `privacy.html` — Privacy Policy (required for App Store / Google Play)

## How to Host for Free

### Option 1: GitHub Pages (Recommended)

1. Create a new GitHub repository (e.g. `signstimator` or `signstimator.com`)
2. Upload the two HTML files (and this README)
3. Go to **Settings → Pages**
4. Set Source to **Deploy from a branch** → `main` / `/ (root)`
5. Save. Your site will be live at `https://yourusername.github.io/repo-name`
6. (Optional) Add your custom domain `signstimator.com` under the same Pages settings

### Option 2: Cloudflare Pages

1. Push the files to a GitHub repo
2. Go to [Cloudflare Pages](https://pages.cloudflare.com) → Create project → Connect the repo
3. Build settings: leave empty (static site) → Deploy
4. Add custom domain if desired

### Option 3: Netlify / Vercel

Same idea — drag & drop the folder or connect the GitHub repo. Zero build command needed.

## Contact Form

The form on the homepage currently points to a placeholder Formspree endpoint.  
To make it work:

1. Create a free account at [formspree.io](https://formspree.io)
2. Create a new form and copy the form ID
3. Replace `YOUR_FORM_ID` in `index.html` with your real form ID

Alternatively you can use Netlify Forms, Getform, or any other free form backend.

## Customization

- Update the email addresses (`hello@signstimator.com`, `privacy@signstimator.com`)
- Adjust the feature list if your app has different calculators
- Change colors by editing the Tailwind config in the `<script>` tag

## Notes for App Store Submission

- Link this Privacy Policy URL in App Store Connect and Google Play Console
- Update the Privacy Policy if you later add analytics, accounts, in-app purchases, or any data collection
