# EduCare Portfolio Website

Static marketing site and privacy policy for the EduCare chemistry learning app, currently focused on Uzbekistan-based learners. Designed for quick deploys on Netlify.

## Project structure

- `index.html` - landing page with hero, chemistry feature highlights, contact form, and App Store links.
- `privacy-policy.html` - Play Store ready privacy policy (update the date, provider name, and contact details as needed).
- `assets/css/styles.css` - shared styling for the landing page.
- `netlify.toml` - Netlify configuration with a clean URL fallback.

## Customization checklist

1. Update copy in `index.html` to match your latest courses, testimonials, or screenshots.
2. Replace the App Store URL placeholder with the published EduCare listing when available.
3. Confirm the contact email, organization name, and Tashkent mailing address in both HTML files.
4. Adjust colors or typography in `assets/css/styles.css` to align with EduCare branding.

## Deploying to Netlify

1. Push this folder to your Git provider (GitHub, GitLab, or Bitbucket).
2. Create a new Netlify site and connect the repository.
3. Leave the build command blank (static site) and set the publish directory to the repository root.
4. Trigger a deploy; Netlify will serve `index.html` as the entry point.

## Local preview

Open `index.html` or `privacy-policy.html` in your browser, or run any static file server (for example, `npx serve .`) from the project root.
