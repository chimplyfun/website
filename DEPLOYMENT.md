# Deployment Guide for Chimply Fun Website

## 🚀 Quick Deployment Steps

### 1. Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" icon in the top right → "New repository"
3. Repository name: `chimplyfun`
4. Make it **Public** (required for free GitHub Pages)
5. **Don't** initialize with README, .gitignore, or license
6. Click "Create repository"

### 2. Upload Your Files
1. In your new repository, click "uploading an existing file"
2. Drag and drop these files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
   - `CNAME`
3. Add commit message: "Initial website upload"
4. Click "Commit changes"

### 3. Enable GitHub Pages
1. Go to repository **Settings** (tab at the top)
2. Scroll down to **Pages** section (left sidebar)
3. Under **Source**, select "Deploy from a branch"
4. Branch: **main** (or **master**)
5. Folder: **/ (root)**
6. Click **Save**

### 4. Set Up Custom Domain
1. In the same **Pages** section
2. Under **Custom domain**, enter: `chimplyfun.com`
3. Click **Save**
4. Check "Enforce HTTPS" (recommended)

### 5. Configure DNS (Domain Provider)
You'll need to configure your domain's DNS settings:

**If using a domain registrar (GoDaddy, Namecheap, etc.):**
- Add a **CNAME** record:
  - Name: `@` or leave empty
  - Value: `yourusername.github.io`
  - TTL: 3600 (or default)

**If using Cloudflare:**
- Add a **CNAME** record:
  - Name: `@`
  - Target: `yourusername.github.io`
  - Proxy status: DNS only (gray cloud)

### 6. Wait for Propagation
- DNS changes can take 24-48 hours
- GitHub Pages may take 5-10 minutes to build
- Your site will be available at `chimplyfun.com`

## 🔧 Troubleshooting

### Site Not Loading?
1. Check repository is **public**
2. Verify GitHub Pages is enabled
3. Check DNS settings
4. Wait for propagation (up to 48 hours)

### Custom Domain Not Working?
1. Verify CNAME file contains `chimplyfun.com`
2. Check DNS records at your domain provider
3. Ensure no conflicting records

### Updates Not Showing?
1. Check if GitHub Pages build is successful
2. Clear browser cache
3. Wait 5-10 minutes for build to complete

## 📱 Testing Your Site

1. **Desktop**: Visit `chimplyfun.com`
2. **Mobile**: Test responsive design
3. **Links**: Verify all navigation works
4. **Forms**: Test contact forms (if added)

## 🔄 Making Updates

1. Edit files locally
2. Upload to GitHub repository
3. Changes deploy automatically in 5-10 minutes
4. No additional steps needed

## 📞 Need Help?

- GitHub Pages documentation: https://pages.github.com/
- GitHub support: https://support.github.com/
- DNS help: Contact your domain provider

---

**Your site will be live at: https://chimplyfun.com** 