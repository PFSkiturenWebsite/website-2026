# PF Skituren Website

A modern, responsive website for PF Skituren - the ski trip for students by students.

## 🎿 About

This is a static website for PF Skituren, the annual ski trip organized by DTU students. The website provides information about the upcoming trip to Alpe d'Huez 2026.

## 🚀 Hosting on GitHub Pages

### Quick Setup

1. Create a new repository on GitHub
2. Push this code to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Click on **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Select the **main** branch and **/ (root)** folder
   - Click **Save**

4. Your site will be live at: `https://YOUR-USERNAME.github.io/YOUR-REPO/`

### Custom Domain (Optional)

To use a custom domain like `pfskituren.dk`:

1. In your repository settings, go to **Pages**
2. Enter your custom domain in the "Custom domain" field
3. Add a `CNAME` file to your repository root with your domain:
   ```
   www.pfskituren.dk
   ```
4. Configure your domain's DNS settings to point to GitHub Pages

## 📁 Project Structure

```
pf-website/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # JavaScript functionality
├── images/             # Image assets (add your own)
└── README.md           # This file
```

## ✨ Features

- Fully responsive design
- Mobile-friendly navigation
- Smooth scroll navigation
- FAQ accordion
- Scroll animations
- Modern CSS with custom properties
- No build process required - just HTML, CSS, and JavaScript

## 🎨 Customization

### Colors

Edit the CSS variables in `css/style.css` to change the color scheme:

```css
:root {
    --primary-color: #1e3a5f;
    --accent-color: #e63946;
    --ice-blue: #a8dadc;
    /* ... more variables */
}
```

### Content

Simply edit `index.html` to update:
- Trip details and dates
- Prices
- Registration links
- FAQ questions and answers
- Contact information

### Images

Add images to the `images/` folder and reference them in the HTML:

```html
<img src="images/your-image.jpg" alt="Description">
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📝 License

This project is created for PF Skituren at DTU.
