# Houston Trailblazers website

Static site (no build step). Files:
- index.html: the whole site (Home, Spring 2027, Fall 2027, Photos & Video, Contact)
- assets/img and assets/video: logo, photos, flyer, videos

## Publish on GitHub Pages
1. Create a new repository on github.com (for example `trailblazers`).
2. Click "Add file" > "Upload files" and drag in index.html, README.md and the assets folder, then Commit.
3. Go to Settings > Pages. Under "Build and deployment" choose "Deploy from a branch", branch `main`, folder `/ (root)`, and Save.
4. After about a minute your site is live at https://YOUR-USERNAME.github.io/REPO-NAME/

## Update later
- Add a photo: save it in assets/img/gallery (a full-size .webp or .jpg), then copy one <figure> block in the Photos & Video section and change its file names and caption. Use data-cat="awards", "community", "team" or "cheer" so the filter buttons work.
- Registration: the form posts to Formspree (form id mgaoqnyv). Payment uses PayPal hosted buttons; edit the PAY list near the bottom of index.html to add one button ID per program.
- Keep each file under 100 MB (GitHub's limit). Videos here are already compressed.
