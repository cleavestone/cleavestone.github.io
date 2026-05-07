# Cleavestone Adungo - Portfolio Website

A professional portfolio website showcasing data science and machine learning projects.

## 🚀 Deployment Instructions (GitHub Pages)

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com) and log in
2. Click the **"+"** icon in the top right → **"New repository"**
3. Name it: `cleavestone.github.io` (replace "cleavestone" with your GitHub username)
4. Make it **Public**
5. Click **"Create repository"**

### Step 2: Upload Your Files
You have two options:

#### Option A: Upload via GitHub Website (Easiest)
1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop all these files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `profile.png`
   - `README.md`
3. Scroll down and click **"Commit changes"**

#### Option B: Upload via Git Command Line
```bash
# Navigate to your project folder
cd path/to/your/portfolio

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial portfolio commit"

# Add remote (replace YOUR-USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select **"main"** branch
5. Click **Save**

### Step 4: Access Your Live Site
Your portfolio will be live at: `https://YOUR-USERNAME.github.io`

⏱️ **Note:** It may take 2-5 minutes for your site to go live after the first deployment.

---

## 🎨 Customization

### Update Your Information
Edit `index.html` to change:
- Contact information
- Project links
- Social media links
- Bio and descriptions

### Change Colors
Edit `styles.css` at the top where CSS variables are defined:
```css
:root {
    --primary: #00D9FF;        /* Main accent color */
    --secondary: #6366F1;      /* Secondary color */
    --bg-dark: #0A0E1A;        /* Background */
    /* ... more variables */
}
```

### Add More Projects
Copy a project card section in `index.html` and modify the content.

---

## 📁 File Structure
```
portfolio/
├── index.html       # Main HTML file
├── styles.css       # Styling
├── script.js        # JavaScript functionality
├── profile.png      # Your profile photo
└── README.md        # This file
```

---

## 🔧 Technologies Used
- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript
- Google Fonts (JetBrains Mono, Crimson Pro)

---

## 📱 Features
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Dark mode theme
- ✅ Smooth scrolling
- ✅ Animated elements on scroll
- ✅ Mobile-friendly navigation
- ✅ Fast loading times
- ✅ SEO optimized

---

## 🆘 Troubleshooting

**Site not showing up?**
- Wait 5 minutes after deployment
- Check that GitHub Pages is enabled in Settings → Pages
- Ensure your repository is public
- Clear your browser cache

**Images not loading?**
- Make sure `profile.png` is uploaded
- Check file names match exactly (case-sensitive)

**Want to use a custom domain?**
- Buy a domain from Namecheap, Google Domains, etc. (~$12/year)
- In GitHub repo Settings → Pages, add your custom domain
- Update your domain's DNS settings (follow GitHub's guide)

---

## 📞 Questions?
Feel free to reach out:
- Email: cleavestone94@gmail.com
- LinkedIn: [Cleavestone Adungo](https://www.linkedin.com/in/cleavestone-adungo-a015b9407/)

---

Built with passion for data science 🚀
