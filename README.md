# SoCal Cleaning Company Landing Page

A responsive static landing page ready for GitHub and Vercel.

## Project files

- `index.html` — complete website with embedded CSS and JavaScript
- `vercel.json` — Vercel routing and security headers
- `.gitignore` — common local and deployment exclusions

## Deploy to Vercel

1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. In Vercel, select **Add New → Project**.
4. Import the GitHub repository.
5. Keep **Framework Preset** set to **Other**.
6. Leave the build command and output directory empty.
7. Click **Deploy**.

## Local preview

Open `index.html` directly in a browser, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Before publishing

Review the phone number, email address, service areas, reviews, images, and form behavior in `index.html`. The current quote form displays an on-page confirmation and does not send submissions to an email or CRM until a form endpoint is connected.
