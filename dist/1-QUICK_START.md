# 🚀 DEPLOY GUIDE

**No Netlify Credits?** Use Vercel, GitHub Pages, or Render (all FREE)

---

## VERCEL (Recommended)

### Step 1: Create Account
- Visit: **vercel.com**
- Click "Sign up" (free)
- Use GitHub, Google, or email

### Step 2: New Project
- Click "New Project"
- Choose "Import Git Repo" OR "Upload"

### Step 3: Upload Dist Folder
- Select `/dist` folder
- Click Deploy

### Step 4: Done ✅
- Site goes live in <1 minute
- Gets URL: `your-project.vercel.app`

---

## GITHUB PAGES

### Step 1: Create Repo
- GitHub.com → New Repository
- Name: `username.github.io`
- Make public

### Step 2: Upload Files
- Upload all `/dist` files
- Into repository root

### Step 3: Enable Pages
- Settings → Pages
- Set source to "main" branch
- Save

### Step 4: Done ✅
- Live at: `username.github.io`
- Takes ~5 minutes

---

## RENDER.COM

### Step 1: Sign Up
- render.com
- Create free account

### Step 2: New Service
- Click "New +"
- Select "Static Site"

### Step 3: Connect
- Upload `/dist` folder
- OR connect GitHub repo

### Step 4: Deploy
- Click Deploy
- Live in ~2 minutes

---

## SURGE.SH (Fastest)

### Step 1: Install
```bash
npm install -g surge
```

### Step 2: Deploy
```bash
surge dist/
```

### Step 3: Choose Domain
- Pick custom domain
- Hit Enter

### Step 4: Done ✅
- Live instantly
- URL shown in terminal

---

## FIREBASE HOSTING (Google)

### Step 1: Create Project
- firebase.google.com
- Create new project (free)

### Step 2: Install CLI
```bash
npm install -g firebase-tools
firebase login
```

### Step 3: Deploy
```bash
firebase deploy
```

### Step 4: Done ✅
- Live at: `project-name.web.app`

---

## RECOMMENDATION

**Pick VERCEL** if:
- Want easiest setup
- Want best performance
- Want auto-deploys
- Want free generous tier

**Pick GITHUB PAGES** if:
- Want permanent free hosting
- Already on GitHub
- Don't need dynamic backend

**Pick SURGE** if:
- Want fastest deployment
- Want simplest CLI
- Don't care about domain

---

**All are 100% free for static sites like this portfolio.**
