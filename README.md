# UCA Scholarship Website Template

This is a GitHub Pages-ready static website for a scholarship program at the University of Central Arkansas.

## Files
- `index.html` - Home page
- `about.html` - About the scholarship
- `requirements.html` - Eligibility and document requirements
- `program.html` - Program benefits and structure
- `applications.html` - Application materials and deadlines
- `process.html` - Review and selection process
- `faqs.html` - Frequently asked questions
- `contact.html` - Contact and inquiry page
- `styles.css` - Site styling
- `script.js` - Mobile menu and FAQ behavior

## Deploy to GitHub Pages

### Option 1: Host in your existing repository `jobair-hossain.github.io`
1. Open your local clone of the repository.
2. Copy all files from this folder into the root of the repo.
3. Commit and push:
   ```bash
   git add .
   git commit -m "Add UCA scholarship website"
   git push origin main
   ```
4. Your site will publish at your GitHub Pages domain.

### Option 2: Host as a project site in repository `scholarship`
1. Create a new repository, for example `scholarship`.
2. Upload all files to the repository root.
3. In GitHub, open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`.
6. Save. GitHub will publish the site at:
   `https://jobair-hossain.github.io/scholarship/`

## Customize Quickly
- Change the program title in the header and page titles.
- Update deadline dates, eligibility rules, email, office location, and application links.
- Replace placeholder scholarship language with your actual award description.
- Add the official approved UCA logo after confirming usage and download access.

## Notes
- The contact form is visual only. To make it send messages, connect it to Formspree, Netlify Forms, or another form backend.
- The site is fully static, so it works well on GitHub Pages.
