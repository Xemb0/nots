# nots

This repository contains a simple static site (index.html) intended to be published with GitHub Pages.

This project was prepared for quick GitHub Pages deployment. If you have the GitHub CLI (`gh`) installed and authenticated, the assistant will attempt to create the remote repo and push for you. Otherwise follow the manual steps below.

Manual deploy steps:
1. Create a GitHub repo (name: `nots`) on github.com.
2. Add the remote: `git remote add origin https://github.com/<your-username>/nots.git`.
3. Push: `git push -u origin main`.
4. In the repo's Settings → Pages, choose branch `main` (root) and save. The site will publish at `https://<your-username>.github.io/nots/`.

Assumptions:
- Repo name will be `nots` (current folder name).
- We publish from `main` branch root.

If you want a user/organization site (username.github.io) tell me and I'll adjust the steps.