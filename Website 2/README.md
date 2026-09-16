# Garage Weekly

A no-build static website for the Car Parking Multiplayer community.

## Publish online

Upload this folder to any static hosting provider. The entry file is `index.html`.

### Netlify

1. Create an account at [Netlify](https://www.netlify.com/).
2. Choose **Add new site** and **Deploy manually**.
3. Drag this project folder into the upload area.
4. Netlify will provide a public URL immediately.

### GitHub Pages

1. Create a GitHub repository and upload `index.html`, `styles.css`, `app.js`, and this README.
2. Open **Settings > Pages**.
3. Set the source to the main branch and the root folder.
4. Open the generated Pages URL.

### Vercel

1. Create a repository with these files.
2. Import the repository at [Vercel](https://vercel.com/).
3. Leave the framework preset empty and use the repository root as the output directory.
4. Deploy.

No build command, package manager, or server is required.

## Important production notes

- Accounts, votes, submissions, and advertiser inquiries currently use browser `localStorage`. They are not shared between users.
- Replace the demo authentication and local inquiry storage with a secure backend before launch.
- PayPal currently uses a hosted checkout handoff. Add PayPal webhooks or server-side order verification before automatically activating paid ad placements.
- The AI Mechanic public lookup needs a deployed HTTPS origin for the most reliable cross-origin API access.
- Add a custom domain, HTTPS, analytics, backups, and a privacy policy before public promotion.
