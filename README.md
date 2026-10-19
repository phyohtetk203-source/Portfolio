# PHK Portfolio

A responsive personal portfolio built with plain HTML, CSS, and JavaScript. No framework or build step is required.

## Included
- `index.html` — portfolio homepage with About, Skills, Projects, and Contact sections
- `projects/todo.html` — task tracker with add, complete, delete, and clear-completed actions; tasks persist in localStorage
- `projects/calculator.html` — calculator with mouse and keyboard support
- `style.css`, `script.js`, `projects/project.css`, `projects/todo.js`, `projects/calculator.css`, `projects/calculator.js`

## Run locally
Open `index.html` in your browser. For best results, use VS Code with the Live Server extension.

## Personalize before publishing
1. Replace `your.email@example.com` with your email.
2. Replace `your-username` with your GitHub username.
3. Edit the About and Skills text so it accurately represents you.
4. Add screenshots or more projects when you have them.

## Publish to GitHub
Create a new empty repository on GitHub, for example `my-portfolio`. Then run these commands in a terminal inside this folder:

```bash
git init
git add .
git commit -m "Build personal portfolio with two mini projects"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/my-portfolio.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username. Your repository link will be:
`https://github.com/YOUR-USERNAME/my-portfolio`

To publish the site with GitHub Pages: open the repository on GitHub → Settings → Pages → select **Deploy from a branch** → choose `main` and `/ (root)` → Save. After publishing, your site URL will typically be `https://YOUR-USERNAME.github.io/my-portfolio/`.
