# Editable Portfolio — Vercel Ready

This is a simple, responsive portfolio made with plain HTML, CSS, and JavaScript.
It does not require a build step, so it is very easy to deploy on Vercel.

## Files

- `index.html` — all portfolio content
- `style.css` — design and responsive layout
- `script.js` — dark mode, mobile menu, animations
- `assets/profile-placeholder.svg` — temporary profile image

## How to edit

Open `index.html` and replace:
- Your Name
- school/university
- About Me text
- skills
- projects
- certificates
- email
- GitHub / LinkedIn / Facebook links

### Replace the profile photo

Put your photo inside `assets/`, for example:

`assets/profile.jpg`

Then change this in `index.html`:

`src="assets/profile-placeholder.svg"`

to:

`src="assets/profile.jpg"`

## Deploy to Vercel

1. Create a GitHub repository.
2. Upload all files from this folder.
3. Open Vercel and choose Add New → Project.
4. Import the GitHub repository.
5. For a plain HTML site, no framework is required.
6. Click Deploy.

Your site will receive a `.vercel.app` address.

## Important

You can edit the files later, push the changes to GitHub, and Vercel will automatically redeploy the updated site.
