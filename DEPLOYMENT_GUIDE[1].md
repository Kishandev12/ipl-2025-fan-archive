# 🚀 How to Host Your IPL 2025 Archive on GitHub Pages

This guide will help you deploy your IPL 2025 Fan Archive as a live website using GitHub Pages (completely free!).

## 📋 What You'll Need

1. A GitHub account (free) - Sign up at https://github.com
2. The 4 files from this project:
   - `index.html` (main archive page)
   - `ipl_2025_omeka_connection.html` (documentation page)
   - `README.md` (repository description)
   - `LICENSE` (license file)

## 🎯 Step-by-Step Instructions

### Step 1: Create a GitHub Account (If You Don't Have One)

1. Go to https://github.com
2. Click "Sign up"
3. Follow the registration process
4. Verify your email address

### Step 2: Create a New Repository

1. Log in to GitHub
2. Click the **"+"** icon in the top-right corner
3. Select **"New repository"**
4. Fill in the details:
   - **Repository name**: `ipl-2025-fan-archive` (or any name you prefer)
   - **Description**: "Digital heritage archive of IPL 2025 fan culture"
   - **Public** (must be public for free GitHub Pages)
   - ✅ Check "Add a README file"
5. Click **"Create repository"**

### Step 3: Upload Your Files

#### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop all 4 files:
   - `index.html`
   - `ipl_2025_omeka_connection.html`
   - `README.md` (replace the auto-generated one)
   - `LICENSE`
3. Scroll down and click **"Commit changes"**
4. Add a commit message like "Initial upload of IPL 2025 Fan Archive"
5. Click **"Commit changes"** again

#### Option B: Using Git Command Line (Advanced)

```bash
# Clone your repository
git clone https://github.com/YOUR-USERNAME/ipl-2025-fan-archive.git
cd ipl-2025-fan-archive

# Copy your files into this folder
# (Place index.html, ipl_2025_omeka_connection.html, README.md, LICENSE here)

# Add all files
git add .

# Commit
git commit -m "Initial upload of IPL 2025 Fan Archive"

# Push to GitHub
git push origin main
```

### Step 4: Enable GitHub Pages

1. In your repository, click **"Settings"** (top menu)
2. In the left sidebar, click **"Pages"** (under "Code and automation")
3. Under "Source", select:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
4. Click **"Save"**
5. GitHub will display a message: "Your site is ready to be published at..."

### Step 5: Wait for Deployment (1-2 minutes)

1. Refresh the Settings → Pages page after 1-2 minutes
2. You'll see: **"Your site is live at https://YOUR-USERNAME.github.io/ipl-2025-fan-archive/"**
3. Click the link to view your live website!

## ✅ Verify Your Website

Your website should now be live at:

```
https://YOUR-USERNAME.github.io/ipl-2025-fan-archive/
```

### Test These Features:

- ✅ Main archive page loads
- ✅ Navigation menu works (Headlines, Reddit, Memes, etc.)
- ✅ SVG graphics display properly
- ✅ Links to external sites work
- ✅ "About Omeka" page loads when clicked
- ✅ Mobile responsive (test on phone)

## 🔧 Troubleshooting

### Problem: 404 Error

**Solution**: 
- Make sure your main file is named `index.html` (not `ipl_2025_archive_enhanced.html`)
- Check that GitHub Pages is enabled in Settings → Pages
- Wait 2-3 minutes for deployment to complete

### Problem: Omeka Link Doesn't Work

**Solution**:
- Make sure `ipl_2025_omeka_connection.html` is uploaded
- File names are case-sensitive on GitHub
- Check that the link in `index.html` matches the exact filename

### Problem: SVG Graphics Don't Show

**Solution**:
- SVGs are embedded in the HTML, so they should work automatically
- Try a different browser (Chrome, Firefox, Safari)
- Clear your browser cache

## 📝 Making Updates

### To Update Your Website:

1. Go to your repository on GitHub
2. Click on the file you want to edit (e.g., `index.html`)
3. Click the pencil icon (✏️) to edit
4. Make your changes
5. Scroll down and click **"Commit changes"**
6. Your website will update automatically in 1-2 minutes!

### Or Upload a New Version:

1. Click **"Add file"** → **"Upload files"**
2. Drag the updated file (it will replace the old one)
3. Commit the changes
4. Wait 1-2 minutes for the update to go live

## 🎨 Customization Tips

### Change the Repository Name:

1. Go to Settings → General
2. Under "Repository name", enter a new name
3. Your URL will change to: `https://YOUR-USERNAME.github.io/NEW-NAME/`

### Add a Custom Domain (Advanced):

1. Buy a domain (e.g., from Namecheap, GoDaddy)
2. Go to Settings → Pages → Custom domain
3. Follow GitHub's instructions to set up DNS
4. Your site will be accessible at `www.your-domain.com`

## 📊 Sharing Your Website

Once live, share your archive:

### For Your Class Presentation:

```
"My digital archive is live at:
https://YOUR-USERNAME.github.io/ipl-2025-fan-archive/

This demonstrates real-world deployment of a digital humanities project
using GitHub Pages as free, open-source infrastructure."
```

### Social Media:

```
🏏 Just launched my IPL 2025 Fan Archive!
📚 Digital heritage project preserving fan culture
🌐 https://YOUR-USERNAME.github.io/ipl-2025-fan-archive/
#DigitalHumanities #IPL2025 #RCB
```

### In Your Resume/Portfolio:

```
IPL 2025 Fan Archive
A digital heritage project documenting ephemeral fan culture using
archival standards (Dublin Core metadata, web archiving).
Live: https://YOUR-USERNAME.github.io/ipl-2025-fan-archive/
GitHub: https://github.com/YOUR-USERNAME/ipl-2025-fan-archive
```

## 🔐 Privacy & Content Notes

### What's Public:

- ✅ Your code/HTML is public (viewable by anyone)
- ✅ Your website is public (indexed by Google)
- ✅ Anyone can visit your website URL

### What's Private:

- ❌ Your GitHub email (unless you choose to display it)
- ❌ Any files you don't upload to the repository
- ❌ Edit access (only you can edit unless you give permission)

### Copyright Compliance:

Your archive **links to** external content (fair use for educational purposes).
You are **not hosting** copyrighted material directly.
All content remains on original sources (ESPNcricinfo, Reddit, Twitter, etc.).

## 🎓 For Your Presentation

### What to Tell Your Ma'am:

```
"I've deployed this archive as a live website using GitHub Pages,
demonstrating:

1. Version control (Git/GitHub)
2. Open-source infrastructure
3. Web hosting and deployment
4. Public accessibility for research
5. Integration with archival standards (Wayback Machine, Dublin Core)

The site is fully functional, mobile-responsive, and uses no external
dependencies—all graphics are embedded SVGs that work offline."
```

### Show Her:

1. **Live URL**: Open the website on your laptop
2. **GitHub Repository**: Show the code on github.com
3. **Mobile Version**: Open on your phone to show responsiveness
4. **Omeka Documentation**: Click through to show the two-tier system

## 🚀 Next Steps After Deployment

### 1. Add to Your Portfolio:
- LinkedIn projects section
- Resume under "Digital Projects"
- GitHub profile README

### 2. Get Analytics (Optional):
- Add Google Analytics to track visitors
- See which sections get the most views

### 3. Expand the Archive:
- Add more fan content as IPL continues
- Include 2026 season when it happens
- Document other cricket tournaments

### 4. Academic Credit:
- Cite your URL in papers: "See [Author]. (2025). IPL 2025 Fan Archive. https://..."
- Reference in your thesis/dissertation
- Share with digital humanities communities

## ❓ Need Help?

### GitHub Support:
- https://docs.github.com/pages

### Common Questions:
- **Q: Is this really free?**
  A: Yes! GitHub Pages is 100% free for public repositories.

- **Q: How long will my site stay live?**
  A: Forever, as long as you keep your GitHub account active.

- **Q: Can I make it private?**
  A: GitHub Pages requires public repositories for free hosting.

- **Q: Will my website URL change?**
  A: Only if you rename your repository or username.

---

## 🎉 Congratulations!

You've just deployed a professional digital humanities archive to the web!

Your URL: `https://YOUR-USERNAME.github.io/ipl-2025-fan-archive/`

Share it with pride! 🏆
