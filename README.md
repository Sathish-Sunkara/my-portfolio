# Sathish Sunkara — Personal Portfolio

A responsive, static personal portfolio website for showcasing ServiceNow AI development experience, project work, skills, credentials and public profiles.

## Files

- `index.html` — page content and structure
- `styles.css` — responsive design and visual styling
- `script.js` — mobile navigation and dynamic footer year
- `assets/favicon.svg` — site icon
- `vercel.json` — static deployment configuration

## Run locally

You can open `index.html` directly in a browser, or run a local static server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub and Vercel

1. Create a new public or private repository on GitHub.
2. Extract this ZIP file.
3. Upload the **contents** of the extracted `sathish-portfolio` folder to the repository root (so `index.html` is at the root).
4. Commit and push the files.
5. In Vercel, choose **Add New → Project** and import the GitHub repository.
6. Framework preset: **Other**.
7. Build command: leave blank.
8. Output directory: `.` (or leave the default for a static site).
9. Select **Deploy**.

Vercel will provide a deployment URL. You can later add a custom domain in the project's **Settings → Domains**.

## Before publishing

Please review these items:
- Confirm that **Senior Analyst** is the designation you are permitted and comfortable to publish.
- Confirm that client/project descriptions are allowed by your employer and client. Client names have deliberately been omitted from the public case studies.
- Add your preferred professional photograph if you want one. The current hero uses a CSS illustration and does not require a photo.
- Add a public contact email if you want recruiters to contact you directly.
- Add certification verification URLs and exact credential issue dates if available.
- Add independent project details when you are ready.

## Editing content

Most text is in `index.html`. Update colors, spacing and typography in `styles.css`. No framework, build step, API key or backend is required.
