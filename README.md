# NAT Network Lab (GitHub Pages)

A static, browser-based NAT learning web app based on the supplied `NAT.pdf` notes.

## Files
- `index.html` — complete responsive GUI, lessons, interactive NAT packet translator, scenarios and quiz.
- `README.md` — these publishing instructions.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in Chrome, Edge or Firefox.
3. No Python, server, database, API key or build step is required.

## Publish with GitHub Pages (step by step)
1. Sign in to https://github.com/ or create an account.
2. Click **New repository**.
3. Enter a repository name, for example `nat-network-lab`.
4. Set it to **Public** (recommended for the free GitHub Pages workflow), then click **Create repository**.
5. On the repository page, click **Add file → Upload files**.
6. Extract this ZIP on your computer. Open the extracted `nat-github-lab` folder.
7. Drag `index.html` and `README.md` into the GitHub upload area. Make sure `index.html` is at the repository root, not inside another nested folder.
8. Enter a commit message such as `Add NAT learning lab`, then click **Commit changes**.
9. Open **Settings → Pages** in the repository.
10. Under **Build and deployment**, choose **Deploy from a branch**.
11. Select branch **main** and folder **/(root)**, then click **Save**.
12. Wait for the deployment to finish. Refresh **Settings → Pages**; GitHub will show your site URL, normally:
    `https://YOUR-USERNAME.github.io/nat-network-lab/`
13. Open that URL. Share it with learners.

## Updating the app
Edit `index.html` locally, then upload the changed file to the same repository and commit the change. GitHub Pages will redeploy automatically.

## Notes
- This is a front-end educational simulator. It does not configure a real Palo Alto firewall or send network packets.
- The example IP addresses are documentation/example addresses for training.
- The lessons follow the uploaded NAT notes. Where the notes say Dynamic DNAT has four main types but enumerate only Static DNAT and Dynamic DNAT, the app explicitly presents the two types named in the notes.
