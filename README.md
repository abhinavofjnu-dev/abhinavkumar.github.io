# Abhinav Kumar - Academic Portfolio

A modern, responsive academic portfolio website built with HTML, CSS, and JavaScript.

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon → **New repository**
3. Name it: `abhinav-kumar.github.io` (replace with your username)
   - Or any name like `portfolio` if you prefer
4. Keep it **Public**
5. Click **Create repository**

### Step 2: Push Your Code

Open terminal in this folder and run:

```bash
git init
git add .
git commit -m "Initial commit - Academic Portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (in left sidebar)
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch and **/ (root)** folder
5. Click **Save**

### Step 4: Access Your Site

Your site will be live at:
- `https://YOUR_USERNAME.github.io/` (if repo named `username.github.io`)
- `https://YOUR_USERNAME.github.io/REPO_NAME/` (for other repo names)

## 📁 Project Structure

```
abhinav-portfolio/
├── index.html      # Main HTML file
├── style.css       # All styling
├── script.js       # Interactive features
└── README.md       # This file
```

## ✨ Features

- Modern, professional academic design
- Fully responsive (mobile, tablet, desktop)
- Smooth scroll navigation
- Animated sections on scroll
- Interactive skill tags
- Timeline-based research experience
- Clean publication cards

## 🎨 Customization

### Add Profile Photo

Replace the avatar placeholder in `index.html`:

```html
<!-- Replace this -->
<div class="avatar-placeholder">AK</div>

<!-- With this -->
<img src="your-photo.jpg" alt="Abhinav Kumar" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
```

### Change Colors

Edit CSS variables in `style.css`:

```css
:root {
    --primary: #1e3a5f;      /* Main blue */
    --accent: #c9a227;       /* Gold accent */
}
```

## 📧 Contact

Abhinav Kumar - maurya.abhinava@gmail.com
