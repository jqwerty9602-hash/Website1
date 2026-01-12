# Swift Logistics - Static Website

A modern, responsive logistics website built with HTML and CSS. Ready for deployment to Vercel.

## Run Locally

1. Open `index.html` in your web browser
2. Or use a local server:
   ```bash
   npx serve
   ```
   Then visit `http://localhost:3000`

## Push to GitHub

1. Initialize Git repository:
   ```bash
   git init
   ```

2. Add all files:
   ```bash
   git add .
   ```

3. Create initial commit:
   ```bash
   git commit -m "Initial commit: logistics website"
   ```

4. Create a new repository on GitHub (do not initialize with README)

5. Add remote and push:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

## Deploy to Vercel

### Option 1: Via Vercel Dashboard (Recommended)

1. Go to [vercel.com](https://vercel.com)
2. Sign in with GitHub
3. Click "Add New Project"
4. Import your GitHub repository
5. Vercel will auto-detect the static site
6. Click "Deploy"

### Option 2: Via Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Login to Vercel:
   ```bash
   vercel login
   ```

3. Deploy:
   ```bash
   vercel
   ```

4. Follow the prompts to complete deployment

## Project Structure

```
/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Styles
├── assets/
│   └── images/        # Image assets (optional)
├── vercel.json        # Vercel configuration
└── README.md          # This file
```

## Features

- Fully responsive design
- Mobile-first approach
- Semantic HTML5
- CSS Grid and Flexbox
- Accessible (WCAG compliant)
- No build tools required
- Zero dependencies

## Tech Stack

- HTML5
- CSS3
- No frameworks
- No JavaScript required

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT
