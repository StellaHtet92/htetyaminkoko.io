# Htet Yamin Ko Ko – Personal Website

Personal academic website hosted on GitHub Pages.

## 🚀 How to host this on GitHub (step by step)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up if you don't have an account.

### Step 2 — Create a new repository
1. Click the **+** button (top right) → **New repository**
2. Name it exactly: `htetyaminkokoedu.github.io`  
   *(Replace `htetyaminkokoedu` with your actual GitHub username)*
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload your files
**Option A — Upload via browser (easiest):**
1. In your new repo, click **Add file** → **Upload files**
2. Upload `index.html` and the `.github/` folder
3. Click **Commit changes**

**Option B — Use Git (if you have it installed):**
```bash
git init
git add .
git commit -m "Initial website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git push -u origin main
```

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **GitHub Actions**
3. Save

### Step 5 — Wait ~2 minutes, then visit:
```
https://htetyaminkokoedu.github.io
```

## ✏️ Updating content
Edit `index.html` directly in GitHub (click the file → pencil icon) or upload a new version. The site redeploys automatically.

## 🔗 Custom domain (optional)
If you have a domain like `htetyaminko.com`, add it in **Settings → Pages → Custom domain**.
