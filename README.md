# PawWalkers - Dog Walking Business Website

A simple, clean, and minimal three-page website for a dog walking business with fake functionality for demonstration purposes.

## Features

- **Three Pages**: Home, Services, and Contact
- **Clean Minimal Design**: Modern UI with gradient headers and card-based layouts
- **Responsive**: Works on desktop, tablet, and mobile devices
- **Fake Form Functionality**: Contact form simulates submission without backend
- **Easy to Deploy**: Ready for GitHub Pages deployment

## File Structure

```
dog-walking-site/
├── index.html          # Home page
├── services.html       # Services page with pricing
├── contact.html        # Contact page with form
├── styles.css          # All styling
├── script.js           # Fake form submission logic
└── README.md           # This file
```

## Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `dog-walking-site`)
4. Make it public
5. Do NOT initialize with README, .gitignore, or license
6. Click "Create repository"

### Step 2: Push Your Code

Open terminal in the `dog-walking-site` directory and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Dog walking website"

# Add your GitHub repository as remote (replace with your username and repo name)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait a few minutes, then your site will be live at:
   `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## Local Testing

To test locally, simply open `index.html` in your web browser:

```bash
# Option 1: Open directly
open index.html

# Option 2: Use Python's built-in server
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Customization

### Change Colors

Edit `styles.css` and modify these color values:
- Primary color (purple): `#667eea`
- Accent color (red): `#ff6b6b`
- Secondary color: `#764ba2`

### Update Content

- **Business Name**: Search for "PawWalkers" and replace with your name
- **Phone/Email**: Update in `contact.html`
- **Pricing**: Modify prices in `services.html`
- **Services**: Add/remove service cards as needed

### Change Form Behavior

Edit `script.js` to modify:
- Success message timing (currently 5 seconds)
- Submission delay (currently 1.5 seconds)

## Technologies Used

- HTML5
- CSS3 (Flexbox & Grid)
- Vanilla JavaScript
- No frameworks or dependencies

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Free to use for personal and commercial projects.
