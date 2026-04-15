# Mo Boroumand — Personal Website

Built with [Quarto](https://quarto.org). Hosted on GitHub Pages.

## 🌐 Live site
👉 `https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPO-NAME`

---

## 🚀 How to deploy (step by step)

### 1. Install Quarto (once)
Download from: https://quarto.org/docs/get-started/

### 2. Install VS Code extension (once)
Install the **Quarto** extension from the VS Code marketplace.

### 3. Preview locally
```bash
quarto preview
```

### 4. Render the site
```bash
quarto render
```
This generates the `docs/` folder which GitHub Pages will serve.

### 5. Push to GitHub
```bash
git add .
git commit -m "Update site"
git push
```

### 6. Enable GitHub Pages (one time only)
1. Go to your repo on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Choose branch: `main`, folder: `/docs`
5. Click **Save**

Your site will be live at:
`https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPO-NAME`

---

> With the GitHub Actions workflow included, every `git push` to `main` will automatically re-render and deploy the site.
