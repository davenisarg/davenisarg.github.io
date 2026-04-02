# davenisarg.github.io

Personal website built with Hugo + Blowfish theme

## How to publish to GitHub Pages

### Step 1: Create the GitHub repo

1. Go to https://github.com/new
2. Repository name: **davenisarg.github.io** (must match your GitHub username exactly)
3. Set to **Public**
4. Do NOT initialize with README (we already have one)
5. Click "Create repository"

### Step 2: Push the code from your computer

```bash
cd /path/to/davenisarg.github.io 

git add -A
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/davenisarg/davenisarg.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repo: https://github.com/davenisarg/davenisarg.github.io/settings/pages
2. Under "Build and deployment" > Source, select **GitHub Actions**
3. That's it. The workflow file (`.github/workflows/deploy.yml`) handles the rest.

### Step 4: Wait ~2 minutes

GitHub Actions will build and deploy automatically. Check progress at:
https://github.com/davenisarg/davenisarg.github.io/actions

Your site will be live at: **https://davenisarg.github.io**

---

## How to add your profile photo

1. Drop your photo into `assets/img/profile.jpg`
2. In `config/_default/params.toml`, uncomment the image line:
   ```toml
   image = "img/profile.jpg"
   ```
3. Commit and push. The site rebuilds automatically.

## How to set up the Instagram feed

The photography page has three options documented in the HTML comments. The easiest:

**Option 1: Elfsight (recommended, free tier)**
1. Go to https://elfsight.com/instagram-feed-widget/
2. Create free account, connect your Instagram (@thedavenisarg)
3. Configure grid layout (3 columns, 9-12 posts)
4. Copy the embed code
5. Paste it into `content/photography/_index.md`, replacing the placeholder
6. Commit and push

**Option 2: Curator.io (free, 1 feed)**
Same idea, different provider. See comments in the photography page.

## Local development

```bash
# Install Hugo (macOS)
brew install hugo

# Run dev server
hugo server -D

# Open http://localhost:1313
```

## Adding a custom domain later

1. Buy a domain from Cloudflare Registrar (~$10/yr): nisargdave.com or nisargdave.dev
2. In Cloudflare DNS, add:
   - Type: CNAME, Name: @, Target: davenisarg.github.io
   - Type: CNAME, Name: www, Target: davenisarg.github.io
3. In GitHub repo Settings > Pages > Custom domain, enter your domain
4. Check "Enforce HTTPS"
5. Update `baseURL` in `config/_default/hugo.toml` to your new domain
