# SP Landing Page

A simple single-page landing site for ships, subbed scenes, and more. Built for GitHub Pages.

## Setup

1. **Create a GitHub repo** – Either:
   - `username.github.io` for a personal site at `https://username.github.io`
   - Or any repo name for `https://username.github.io/repo-name`

2. **Push this project** to that repo:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages** – Repo → Settings → Pages → Source: Deploy from branch → Branch: `main` (root)

4. **Fill in your content** in `index.html`:
   - Ship names, descriptions, drive links
   - App GitHub URL and description
   - About me text
   - Add ship images to `images/` (e.g. `ship1-a.jpg`, `ship2-a.jpg`)

## Structure

- **Ships** – Cards with drive links, descriptions, and images
- **App** – Info about your GitHub app
- **About me** – Short bio
- **More** – Placeholder for future content

## Images

Put ship images in the `images/` folder. Reference them in the ship cards like:
```html
<img src="images/ship-name-a.jpg" alt="Ship name">
```

## Preview the page 

### Local server. Run in your Terminal from the project folder:

```bash
cd /Users/kszxvd/SP-landingpage
python3 -m http.server 8000
```
Then visit: `http://localhost:8000`
