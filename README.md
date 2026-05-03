# Awake Money Website

A modern, beautiful redesign of the Awake Money landing page - Your Super Wallet for the Age of AI Agents.

## Features

- ✨ Modern, clean design with smooth animations
- 🎨 Gradient backgrounds and glassmorphism effects
- 📱 Fully responsive (mobile, tablet, desktop)
- 🚀 Optimized for performance
- 💜 Preserves all original content and branding
- 🌐 Ready for GitHub Pages deployment

## Local Development

Simply open `index.html` in your browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## Deploy to GitHub Pages

### Option 1: Direct Deploy (Recommended)

1. **Create a new GitHub repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Awake Money redesign"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click `Settings` > `Pages`
   - Under "Source", select `main` branch
   - Select `/ (root)` folder
   - Click `Save`
   - Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### Option 2: Using GitHub Desktop

1. Open GitHub Desktop
2. File > Add Local Repository > Select this folder
3. Publish repository to GitHub
4. Go to repository settings on GitHub.com
5. Enable GitHub Pages (Settings > Pages > main branch)

### Option 3: Custom Domain

If you want to use a custom domain:

1. Create a file named `CNAME` with your domain:
   ```
   awakemoney.com
   ```

2. Configure your DNS:
   - Add a CNAME record pointing to `YOUR_USERNAME.github.io`
   - Or A records pointing to GitHub's IPs

## Project Structure

```
awake-money-web/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css      # All styles
│   ├── js/
│   │   └── main.js        # Animations & interactions
│   └── images/
│       ├── image01.jpg    # Main visual
│       ├── image03.png    # Launch section
│       └── image05.png    # Platform section
└── README.md
```

## Design Features

- **Typography**: Space Grotesk for headings, Inter for body text
- **Colors**: Purple (#695EE6), Pink (#FF7A7A), Lavender (#C685D6), Gold (#FFD700)
- **Animations**: Smooth scroll reveals, floating gradient orbs, parallax effects
- **Layout**: Modern grid-based responsive design with glassmorphism cards

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contact

For inquiries about Awake Money:
- Email: contact@awake.money
- Location: San Mateo, CA

---

**An Awake Platform** | Built with modern web technologies
