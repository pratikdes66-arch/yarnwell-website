# Yarnwell – Crochet Patterns Shop

A modern, responsive, and self-contained static website for modern crochet patterns and kits.

## 📁 Project Structure

```text
yarnwell-website/
├── index.html       # Full website (HTML, responsive CSS, interactive JS, embedded SVG/images)
├── vercel.json      # Vercel deployment settings and security headers
├── .gitignore       # Git ignore rules for build and system artifacts
└── README.md        # Documentation and deployment guide
```

---

## 🚀 How to Upload to GitHub

### Option A: Using Git CLI (Recommended)

1. Open your terminal in this directory:
   ```bash
   cd "C:\Users\dell\.gemini\antigravity\scratch\yarnwell-website"
   ```

2. Initialize a git repository and commit the files:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Yarnwell crochet shop website"
   git branch -M main
   ```

3. Create a new repository on [GitHub](https://github.com/new) (e.g., `yarnwell-website`). Keep it **Public** or **Private**, but leave "Initialize this repository with a README" unchecked.

4. Connect to your GitHub repository and push:
   ```bash
   git remote add origin https://github.com/<YOUR-USERNAME>/yarnwell-website.git
   git push -u origin main
   ```

### Option B: Upload via Web Browser (GitHub Website)

1. Create a new repository at [github.com/new](https://github.com/new).
2. Click **uploading an existing file**.
3. Drag and drop all files (`index.html`, `vercel.json`, `.gitignore`, `README.md`) into GitHub.
4. Click **Commit changes**.

---

## ⚡ How to Deploy on Vercel

### Option 1: Deploy with GitHub Integration (Automatic CI/CD)

1. Go to [vercel.com](https://vercel.com) and sign in (using GitHub is quickest).
2. Click **"Add New..."** > **"Project"**.
3. Under **Import Git Repository**, select your `yarnwell-website` repository.
4. In the configuration screen:
   - **Framework Preset**: *Other* (detected automatically as a static site)
   - **Root Directory**: `./` (default)
5. Click **"Deploy"**.
6. Within seconds, your site will be live with a free `*.vercel.app` domain and free SSL!

### Option 2: Deploy directly via Vercel CLI

If you have Node.js installed, run:
```bash
npx vercel
```
Follow the prompts to link your project, and Vercel will output your live deployment URL immediately.
