# ApplyFlow — Job Application Tracker

A lightweight, responsive job application tracker built with vanilla HTML, CSS, and JavaScript.

## Features
- Create, edit, and delete job application records
- Track company, role, status, date, posting URL, and next-step notes
- Search applications and filter by status
- Summary counters for total applications, in-progress applications, interviews, and offers
- Export records to CSV
- Optional sample data to let reviewers explore the interface
- Browser-local persistence with `localStorage`

## Run locally
Open `index.html` in a modern browser. No build step, server, package manager, API key, or external dependency is required.

## Create the first Git commit
1. Extract this ZIP file.
2. Open a terminal in the `applyflow-demo` folder.
3. Run:

```bash
git init
git add index.html README.md
git commit -m "Initial commit: ApplyFlow job tracker"
```

4. Create an empty repository on GitHub (for example, `applyflow-demo`), then connect and push it using the repository URL GitHub provides:

```bash
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/applyflow-demo.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username.

## Publish a live URL
For the fastest manual deployment, open https://app.netlify.com/drop and drag the extracted `applyflow-demo` folder onto the page. Netlify will provide a public `netlify.app` URL. Alternatively, connect the GitHub repository to Netlify for automatic deployments on future pushes.

Record the actual time between your first Git commit and the successful live deployment. Do not estimate it after the fact.

## Technical notes
This is a front-end demonstration, not an AI-powered app or multi-user service. Records remain in the browser's local storage on the device where they were entered; they are not synced to a server. Use sample data for public demonstrations.
