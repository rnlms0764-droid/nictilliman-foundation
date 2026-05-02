# Deployment Instructions for The NicTilliman Foundation Website

## Option 1: Vercel (Recommended - Easiest)

### Step 1: Create Vercel Account
1. Go to https://vercel.com
2. Sign up with GitHub, GitLab, or email

### Step 2: Deploy
1. Download the `nictilliman-foundation` folder
2. Go to https://vercel.com/new
3. Drag and drop the folder OR import from GitHub
4. Click "Deploy"
5. Your site will be live in seconds with a free `.vercel.app` domain

### Custom Domain (Optional)
1. In Vercel dashboard, go to your project
2. Click "Settings" → "Domains"
3. Add your custom domain

---

## Option 2: GitHub Pages (Free)

### Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Name it `nictilliman-foundation`
3. Make it public

### Step 2: Upload Files
1. Upload all files from the `nictilliman-foundation` folder
2. Commit the files

### Step 3: Enable GitHub Pages
1. Go to repository Settings
2. Scroll to "Pages" section
3. Source: Deploy from a branch
4. Branch: main / (root)
5. Click Save
6. Your site will be at: `https://yourusername.github.io/nictilliman-foundation`

---

## Option 3: Netlify (Free)

### Step 1: Create Netlify Account
1. Go to https://netlify.com
2. Sign up with GitHub or email

### Step 2: Deploy
1. Go to https://app.netlify.com/drop
2. Drag and drop the `nictilliman-foundation` folder
3. Your site is instantly live!

---

## Option 4: Surge.sh (Free, Command Line)

```bash
# Install surge
npm install -g surge

# Navigate to website folder
cd nictilliman-foundation

# Deploy
surge

# Follow prompts to create account and deploy
```

---

## Files to Deploy

Make sure these files are included:
- index.html
- about.html
- mission.html
- events.html
- donate.html
- contact.html
- styles.css
- main.js
- README.md (optional)

---

## After Deployment

Once deployed, share the URL with me and I can:
1. Verify everything works correctly
2. Help set up a custom domain
3. Make any needed updates

## Need Help?

If you need assistance with deployment, I can:
- Walk you through any of these steps
- Make adjustments to the code
- Help troubleshoot issues

The website is ready to go - just pick your preferred hosting option!
