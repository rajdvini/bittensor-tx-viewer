# 🚀 Deployment Guide - Bittensor TX Viewer

## Quick Deploy to GitHub Pages (5 minutes)

### Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **+** icon (top right) → **New repository**
3. Repository settings:
   - **Name**: `bittensor-tx-viewer` (or any name you prefer)
   - **Description**: "Bittensor blockchain transaction viewer with CSV export"
   - **Public** (required for free GitHub Pages)
   - ✅ Check "Add a README file" (you'll replace it)
   - Choose **MIT License**
4. Click **Create repository**

### Step 2: Upload Files

**Option A: Via GitHub Web Interface (Easiest)**

1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop these files:
   - `index.html`
   - `README.md`
   - `LICENSE`
   - `.gitignore`
3. Scroll down, add commit message: "Initial commit - Bittensor TX Viewer"
4. Click **Commit changes**

**Option B: Via Git Command Line**

```bash
# Download the files first, then:

# Initialize git in your project folder
cd path/to/your/files
git init

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/bittensor-tx-viewer.git

# Add all files
git add .

# Commit
git commit -m "Initial commit - Bittensor TX Viewer"

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under "Source":
   - Select branch: **main**
   - Select folder: **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes for deployment

### Step 4: Get Your Live URL

Your site will be live at:
```
https://YOUR-USERNAME.github.io/bittensor-tx-viewer/
```

Example: `https://johndoe.github.io/bittensor-tx-viewer/`

## 🎉 You're Done!

Visit your URL to see the live app. Share it with others!

## 📝 Update Your README

Don't forget to update the README.md with:
- Your actual GitHub Pages URL
- Your wallet address for tips
- Your contact information

## 🔧 Making Changes

To update your site:

1. Edit files locally or on GitHub
2. Commit changes:
   ```bash
   git add .
   git commit -m "Update: description of changes"
   git push
   ```
3. GitHub Pages will automatically rebuild (takes 1-2 minutes)

## 🌐 Custom Domain (Optional)

Want a custom domain like `bittensor-viewer.com`?

1. Buy a domain (Namecheap, GoDaddy, etc.)
2. In repository Settings → Pages → Custom domain
3. Enter your domain
4. Update your domain's DNS settings:
   ```
   Type: CNAME
   Name: www
   Value: YOUR-USERNAME.github.io
   ```
5. Wait for DNS propagation (up to 24 hours)

## 📊 Analytics (Optional)

Add Google Analytics:

1. Get your GA tracking code
2. Add to `index.html` before `</head>`:
   ```html
   <!-- Google Analytics -->
   <script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
   <script>
     window.dataLayer = window.dataLayer || [];
     function gtag(){dataLayer.push(arguments);}
     gtag('js', new Date());
     gtag('config', 'YOUR-GA-ID');
   </script>
   ```

## 🎯 Alternative Hosting Options

### Vercel (Very Fast)
```bash
npm i -g vercel
vercel --prod
```

### Netlify (Drop & Drop)
1. Go to [netlify.com](https://netlify.com)
2. Drag your folder to "Sites"
3. Done!

### Cloudflare Pages
1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Connect your GitHub repository
3. Deploy with one click

## 🆘 Troubleshooting

**Site not loading after 5 minutes?**
- Check Settings → Pages shows "Your site is live"
- Clear browser cache
- Try incognito mode

**404 error?**
- Make sure file is named `index.html` (lowercase)
- Check repository is Public
- Verify branch is set to "main"

**Changes not showing?**
- Wait 1-2 minutes for rebuild
- Do a hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)

**API not working?**
- Check browser console for CORS errors
- Subscan API might be rate limiting
- Try a different wallet address

## 💡 Tips

1. **Custom subdomain**: Your-username.github.io can host multiple projects
2. **Free SSL**: GitHub Pages includes HTTPS automatically
3. **Fast CDN**: GitHub uses a global CDN for fast loading
4. **No server needed**: It's all static files

## 📧 Need Help?

- Check GitHub Pages documentation
- Open an issue in your repository
- Search Stack Overflow for "GitHub Pages"

---

**Ready to claim your $1,000 USDC?** Make sure to:
- ✅ Deploy to GitHub Pages
- ✅ Make repository public
- ✅ Test with a real Bittensor address
- ✅ Send the link!
