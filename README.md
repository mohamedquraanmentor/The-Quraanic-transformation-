# 🌟 The Quraanic Transformation - Landing Page

Premium landing page for "The Quraanic Transformation" - an elite Qur'anic recitation mentorship program.

## 📦 Package Contents

```
quraanic-transformation/
├── index.html              # Main landing page
├── images/                 # All images
│   ├── mentor-main.jpg    # Professional mentor photo
│   ├── avatar-1.jpg       # Student avatar 1
│   ├── avatar-2.jpg       # Student avatar 2
│   └── avatar-3.jpg       # Student avatar 3
└── README.md              # This file
```

---

## 🚀 Quick Start - Deploy to GitHub Pages

### Option 1: Upload via GitHub Website (Easiest)

1. **Go to your GitHub repository**
2. **Click "Add file" → "Upload files"**
3. **Drag and drop ALL files** (index.html + images folder)
4. **Commit changes** with message: "Deploy landing page"
5. **Go to Settings → Pages**
6. **Select branch**: `main` and folder: `/ (root)`
7. **Save** and wait 1-2 minutes
8. **Visit**: `https://YOUR-USERNAME.github.io/REPO-NAME`

### Option 2: Git Command Line

```bash
# Clone your repo
git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
cd REPO-NAME

# Copy all files from this package
cp -r /path/to/this/package/* .

# Commit and push
git add .
git commit -m "Deploy Quraanic Transformation landing page"
git push origin main

# Enable GitHub Pages in Settings → Pages
```

---

## ✅ Post-Deployment Checklist

- [ ] All images showing correctly?
- [ ] Dark/Light theme toggle working?
- [ ] Application form opens?
- [ ] FAQ accordion working?
- [ ] Mobile responsive (test on phone)?
- [ ] Hard refresh browser (Ctrl+Shift+R / Cmd+Shift+R)

---

## 🖼️ Images Already Included

All images are in the `images/` folder with correct names:
- ✅ `mentor-main.jpg` - Your professional photo
- ✅ `avatar-1.jpg`, `avatar-2.jpg`, `avatar-3.jpg` - Student avatars

**No need to change anything** - just upload!

---

## 🎨 Features

### ✨ Design
- Dark/Light theme toggle (with localStorage persistence)
- Premium gold (#D4AF37) and obsidian black (#080808) color scheme
- Playfair Display (headers) + Inter (body) typography
- Smooth animations and transitions
- Fully responsive (desktop, tablet, mobile)

### 🔥 Sections
1. **Hero** - Identity + Promise (with floating student avatars)
2. **Outcomes** - Social proof (300+ students, 99% mastery, 10+ years)
3. **Authority** - Mentor bio with gold-framed photo
4. **Roadmap** - 4-phase transformation methodology
5. **Testimonials** - Student success stories
6. **Exclusion** - "Who this is NOT for" (elite positioning)
7. **FAQ** - Spiritual guidance accordion
8. **Application Modal** - Complete form with:
   - Progress bar
   - Qur'an recitation upload
   - Personal photo upload (optional)
   - All required fields

---

## 🔧 Troubleshooting

### Images not showing?
1. Make sure `images/` folder is uploaded
2. Check file names are **exact**: `mentor-main.jpg` (lowercase, no spaces)
3. Clear browser cache: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
4. Wait 2-5 minutes for GitHub Pages to rebuild

### Page not updating?
1. Clear cache and hard refresh
2. Check GitHub Actions tab for build status
3. Verify GitHub Pages is enabled (Settings → Pages)

---

## 📝 Customization

### Change Colors
Edit in `<style>` section:
```css
:root {
    --gold: #D4AF37;        /* Change gold color */
    --bg-primary: #080808;  /* Change background */
}
```

### Change Text
All text is directly in HTML - search and replace:
- Mentor name: "Mohamed Abdul-Maqsoud"
- Stats: "300+", "99%", "150"

---

## 🎉 You're Done!

Everything is ready to go. Just upload and watch your landing page come to life!

**Live URL will be:** `https://YOUR-USERNAME.github.io/REPO-NAME`

---

© 2026 The Quraanic Transformation · All Rights Reserved
