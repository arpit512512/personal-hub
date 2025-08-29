# Deployment Guide

This guide will walk you through deploying your personal website to Vercel with GitHub integration.

## 🚀 Quick Start

### 1. Initialize Git Repository

```bash
# Initialize git repository
git init

# Add all files
git add .

# Make initial commit
git commit -m "Initial commit: Personal website"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/personal-hub.git

# Push to GitHub
git push -u origin main
```

### 2. Deploy to Vercel

#### Option A: Via Vercel Dashboard (Recommended)

1. Go to [vercel.com](https://vercel.com) and sign up/login
2. Click "New Project"
3. Import your GitHub repository
4. Vercel will automatically detect it's a static site
5. Click "Deploy"
6. Your site will be live at `https://your-project.vercel.app`

#### Option B: Via Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Login to Vercel
vercel login

# Deploy
vercel

# Follow the prompts to link to your GitHub repo
```

### 3. Custom Domain (Optional)

1. In your Vercel dashboard, go to your project
2. Click "Settings" → "Domains"
3. Add your custom domain
4. Update DNS records as instructed by Vercel

## 🔄 Continuous Deployment

Once connected to GitHub:
- Every push to `main` branch automatically triggers a new deployment
- Preview deployments are created for pull requests
- You can rollback to previous deployments if needed

## 📝 Post-Deployment Checklist

- [ ] Update `package.json` with your actual GitHub repository URL
- [ ] Update `sitemap.xml` with your actual domain
- [ ] Update `robots.txt` with your actual domain
- [ ] Test all links and forms
- [ ] Check mobile responsiveness
- [ ] Verify SEO meta tags
- [ ] Test loading speed

## 🛠️ Local Development

```bash
# Install dependencies (optional)
npm install

# Start local development server
npm run dev

# Or use Python
python -m http.server 8000
```

## 📊 Analytics (Optional)

Consider adding analytics to track visitors:

### Google Analytics
Add this to your `<head>` section in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### Vercel Analytics
If you have a Vercel Pro account, you can enable built-in analytics in your project settings.

## 🔧 Troubleshooting

### Common Issues

1. **Build fails**: Check that `index.html` is in the root directory
2. **404 errors**: Ensure `vercel.json` is properly configured
3. **Styling issues**: Clear browser cache and check CSS paths
4. **Domain not working**: Verify DNS settings and wait for propagation

### Support

- [Vercel Documentation](https://vercel.com/docs)
- [GitHub Pages Alternative](https://pages.github.com/)
- [Netlify Alternative](https://www.netlify.com/)

---

Your website should now be live and automatically updating with every GitHub push! 🎉
