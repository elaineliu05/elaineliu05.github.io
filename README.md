# Portfolio Website

A modern, cozy, nature-inspired portfolio site built for GitHub Pages.

## 🌿 Features

- Clean, modern design with earthy color palette
- Fully responsive (mobile, tablet, desktop)
- Smooth scrolling and subtle animations
- Project showcase section
- Contact links (email, GitHub, LinkedIn)

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - This special naming convention makes it your main GitHub Pages site
3. Set it to **Public**
4. Don't initialize with README (we already have files)

### Step 2: Push Your Site

```bash
# Navigate to your portfolio site folder
cd portfolio-site

# Initialize git repository
git init

# Add all files
git add .

# Make your first commit
git commit -m "Initial portfolio site"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages (if not automatic)

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (in the sidebar)
3. Under **Source**, select **main** branch
4. Click **Save**

Your site will be live at `https://yourusername.github.io` in a few minutes!

## ✏️ Customization

### Update Your Information

Open [index.html](index.html) and replace:

- `Your Name` → Your actual name
- `your.email@example.com` → Your email
- `yourusername` → Your GitHub/LinkedIn username
- Update the hero subtitle and about section with your story
- Add links to your actual projects

### Change Colors

Edit [styles.css](styles.css) at the top where CSS variables are defined:

```css
:root {
    --sage: #7a9e7e;          /* Main green */
    --terracotta: #c97d5d;    /* Accent color */
    --cream: #f5f1e8;         /* Background */
    /* Modify these to match your preferred palette */
}
```

### Add More Projects

Copy a project card in [index.html](index.html) and modify:

```html
<div class="project-card">
    <div class="project-icon">🌟</div>
    <h3 class="project-title">Your Project Name</h3>
    <p class="project-description">Description here...</p>
    <div class="project-tags">
        <span class="tag">Tech 1</span>
        <span class="tag">Tech 2</span>
    </div>
    <div class="project-links">
        <a href="https://github.com/yourusername/project" class="project-link">View Project →</a>
    </div>
</div>
```

## 📁 File Structure

```
portfolio-site/
├── index.html    # Main HTML file
├── styles.css    # All styling
├── script.js     # Interactive features
└── README.md     # This file
```

## 🎨 Color Palette

- **Sage Green**: Main brand color, buttons, accents
- **Cream/Beige**: Backgrounds, soft tones
- **Terracotta**: Accent for visual interest
- **Charcoal**: Text color
- **Warm White**: Card backgrounds

## 📱 Responsive Breakpoints

- Desktop: 1100px+ (full width)
- Tablet: 768px - 1099px
- Mobile: < 768px (single column layout)

## 🔧 Future Enhancements

Ideas to expand your portfolio:

- Add a blog section
- Include a resume/CV download
- Add project detail pages
- Integrate with a CMS (like Contentful)
- Add dark mode toggle
- Include testimonials section
- Add analytics (Google Analytics, Plausible)

## 📝 License

This template is free to use for your personal portfolio. Customize it however you like!

---

Built with ❤️ and deployed on GitHub Pages
