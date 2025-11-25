# 🎮 Patoo Game - Official Website

Official website for the Patoo mobile game, hosted on GitHub Pages.

## 🌐 Live Site

The site is accessible at: **https://carokyp.github.io/Patoo-Game-Site/**

## 📁 Project Structure

```
Patoo-Game-Site/
├── index.html          # Main landing page
├── privacy.html        # Privacy policy
├── styles.css          # CSS stylesheet
├── app-ads.txt         # AdMob configuration
└── README.md           # This file
```

## ✨ Features

- 🎨 **Modern and responsive design**: Adapts to all screens (mobile, tablet, desktop)
- 🚀 **Optimized performance**: Fast and smooth loading
- 📱 **Download section**: Link to Google Play Store
- 🎯 **Features showcase**: Highlighting the game's strengths
- 📸 **Screenshot gallery**: Visual preview of the game
- 🔒 **Privacy policy**: Dedicated page for data transparency
- 💰 **AdMob configuration**: app-ads.txt file for monetization

## 🚀 Deployment on GitHub Pages

### Step 1: Push the code to GitHub

1. **Initialize the Git repository** (if not already done):
   ```bash
   cd "Patoo-Game-Site"
   git init
   git add .
   git commit -m "Initial commit - Patoo website"
   ```

2. **Create a new repository on GitHub**:
   - Go to [github.com](https://github.com)
   - Click the "+" button in the top right → "New repository"
   - Name the repository: `Patoo-Game-Site`
   - **Do NOT check** "Initialize with README"
   - Click "Create repository"

3. **Connect and push to GitHub**:
   ```bash
   git remote add origin https://github.com/Carokyp/Patoo-Game-Site.git
   git branch -M main
   git push -u origin main
   ```

### Step 2: Enable GitHub Pages

1. On GitHub, go to your repository's **Settings**
2. In the left menu, click on **Pages**
3. Under "Source":
   - Select the branch: **main**
   - Select the folder: **/ (root)**
4. Click **Save**
5. Wait 1-2 minutes for the site to be deployed

✅ Your site will be available at: `https://carokyp.github.io/Patoo-Game-Site/`

## 📝 AdMob Configuration

The `app-ads.txt` file is already created with a placeholder ID. **Don't forget to modify it!**

### How to get your AdMob Publisher ID:

1. Go to [AdMob Console](https://apps.admob.com/)
2. Log in to your account
3. Go to **Settings** → **Account information**
4. Copy your **Publisher ID** (format: `pub-XXXXXXXXXXXXXXXX`)

### Update app-ads.txt:

Open the `app-ads.txt` file and replace `pub-0000000000000000` with your real Publisher ID:

```
google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f08c47fec0942fa0
```

⚠️ **IMPORTANT**: This modification is essential for AdMob to work properly!

## 🎨 Customization

### Change Colors

Open `styles.css` and modify the CSS variables in `:root`:

```css
:root {
    --primary-color: #6C63FF;    /* Primary color */
    --secondary-color: #FF6B6B;  /* Secondary color */
    --accent-color: #4ECDC4;     /* Accent color */
}
```

### Add Screenshots

1. Create an `images/` folder in your project
2. Add your screenshots (formats: .jpg, .png, .webp)
3. Modify `index.html` to replace the placeholders:

```html
<div class="screenshot-item">
    <img src="images/screenshot1.png" alt="Gameplay Patoo">
</div>
```

### Add Google Play Link

In `index.html`, find the download section and replace the `#` with your link:

```html
<a href="https://play.google.com/store/apps/details?id=your.package.name" class="download-btn">
```

## 📧 Contact

For any questions or modifications, contact me via:
- **GitHub**: [@Carokyp](https://github.com/Carokyp)
- **Email**: contact@patoogame.com (to be configured)

## 📄 License

© 2025 Patoo Game. All rights reserved.

---

**Made with ❤️ for Patoo Game**
