# GitHub Setup Guide

Quick guide to get your Public Health Data Catalog live on GitHub.

## 📋 Prerequisites

- GitHub account ([sign up here](https://github.com/join))
- Git installed on your computer ([download here](https://git-scm.com/downloads))
- Text editor (VS Code, Sublime, Atom, etc.)

## 🚀 Quick Setup (5 minutes)

### Step 1: Create Repository

1. Go to [GitHub](https://github.com)
2. Click the **+** icon → **New repository**
3. Fill in:
   - **Repository name**: `public-health-data-catalog`
   - **Description**: `Interactive catalog of 90+ public health data sources for students and researchers`
   - **Visibility**: Public ✓
   - **Initialize**: Skip (we have files already)
4. Click **Create repository**

### Step 2: Prepare Your Files

Make sure you have these files ready:
```
your-folder/
├── public_health_data_catalog.html
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
└── .gitignore
```

### Step 3: Initialize Git

Open terminal/command prompt in your folder:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Create first commit
git commit -m "Initial commit: Public Health Data Catalog v1.0.0"

# Connect to GitHub (replace YOUR-USERNAME)
git remote add origin https://github.com/YOUR-USERNAME/public-health-data-catalog.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings**
3. Scroll to **Pages** (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait 1-2 minutes
7. Your site will be live at: `https://YOUR-USERNAME.github.io/public-health-data-catalog/public_health_data_catalog.html`

## 🎨 Customize Your Repository

### Add Topics

Add searchable topics to your repository:
1. Go to repository main page
2. Click ⚙️ next to **About**
3. Add topics:
   - `public-health`
   - `data-catalog`
   - `epidemiology`
   - `education`
   - `interactive-visualization`
   - `digital-health`
4. Click **Save changes**

### Update README

Replace placeholder text in README.md:
- `YOUR-USERNAME` → your GitHub username
- `[Your website]` → your actual website
- `[Your email]` → your contact email
- Add your social media links

### Create Repository Description

Add a catchy description:
```
🏥 Interactive catalog of 90+ public health data sources | Built for AI in Public Health course | University of Arizona
```

### Add Repository Image

1. Create a screenshot of your catalog
2. Go to Settings → Options
3. Upload to **Social preview**

## 📱 Share Your Catalog

### For Students

Create a shortened URL for easy sharing:

1. Go to [bit.ly](https://bit.ly) or [tinyurl.com](https://tinyurl.com)
2. Enter your GitHub Pages URL
3. Create custom short link: `bit.ly/uaph-datacatalog`
4. Share in Canvas, Slack, email

### For Course Syllabus

Add to your syllabus:
```markdown
**Public Health Data Catalog**
Access 90+ curated data sources for your projects and research.
Link: https://bit.ly/uaph-datacatalog
```

### For Social Media

Tweet about it:
```
🚀 Just launched an interactive catalog of 90+ #PublicHealth data sources! 

Perfect for students, researchers & practitioners exploring #AI applications in health.

Features real-time search, category filters & a futuristic design ✨

Check it out: [your-link]

#DigitalEpidemiology #DataScience
```

## 🔧 Advanced Setup

### Add Custom Domain (Optional)

If you have a domain like `dataresources.yourdomain.edu`:

1. Create a file named `CNAME` in your repository
2. Add your domain: `dataresources.yourdomain.edu`
3. Commit and push
4. Configure DNS at your domain provider:
   - Type: `CNAME`
   - Name: `dataresources`
   - Value: `YOUR-USERNAME.github.io`
5. In GitHub Settings → Pages, enter custom domain
6. Wait for DNS propagation (up to 24 hours)

### Enable Discussions

Create a community space:
1. Settings → General
2. Enable **Discussions**
3. Create categories:
   - 💡 Ideas (for new data sources)
   - 🙋 Q&A (for questions)
   - 📣 Announcements
   - 🐛 Bug Reports

### Add Issue Templates

Create `.github/ISSUE_TEMPLATE/` folder with:

**bug_report.md:**
```markdown
---
name: Bug Report
about: Report a problem
title: '[BUG] '
labels: bug
---

**Describe the bug**
A clear description of what's wrong.

**To Reproduce**
Steps to reproduce the behavior.

**Expected behavior**
What should happen.

**Screenshots**
If applicable.

**Browser** (if relevant)
- Browser: [e.g. Chrome, Safari]
- Version: [e.g. 98]
```

**data_source_request.md:**
```markdown
---
name: Data Source Request
about: Suggest a new data source
title: '[NEW SOURCE] '
labels: enhancement
---

**Data Source Name**

**URL**

**Organization**

**Description**
Brief description of what data is available.

**Why should we add it?**
Explain the value for students/researchers.
```

### Set Up Branch Protection

Protect your main branch:
1. Settings → Branches
2. Add rule for `main`
3. Enable:
   - ✓ Require pull request reviews
   - ✓ Require status checks to pass
4. Save changes

## 📊 Track Usage

### Enable Insights

Monitor your catalog's impact:
1. Go to **Insights** tab
2. Check:
   - Traffic → Views and unique visitors
   - Forks → Who's reusing it
   - Stars → Community interest
   - Network → Repository relationships

### Add Analytics (Optional)

For detailed analytics:
1. Create [Google Analytics](https://analytics.google.com) account
2. Add tracking code to `<head>` section
3. Monitor user behavior, popular searches, etc.

## 🔄 Keeping It Updated

### Regular Maintenance

Create a schedule:
- **Weekly**: Check for broken links
- **Monthly**: Add new data sources
- **Quarterly**: Update descriptions
- **Annually**: Major version updates

### Using GitHub Actions (Optional)

Automate link checking (advanced):

Create `.github/workflows/link-check.yml`:
```yaml
name: Check Links
on:
  schedule:
    - cron: '0 0 * * 0'  # Weekly on Sunday
  workflow_dispatch:

jobs:
  linkchecker:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Link Checker
        uses: lycheeverse/lychee-action@v1
        with:
          args: --verbose --no-progress '**/*.html'
```

## 🎓 For Teaching

### Create Student Fork Template

1. Create a `student-template` branch
2. Simplify for student exercises
3. Add TODO comments
4. Students can fork and complete

### Assignment Ideas

- **Assignment 1**: Add 5 new data sources
- **Assignment 2**: Improve descriptions
- **Assignment 3**: Add new category
- **Assignment 4**: Fix accessibility issues
- **Assignment 5**: Create API documentation

## 🐛 Troubleshooting

### Pages Not Deploying?

1. Check Settings → Pages → Build status
2. Ensure file is named exactly: `public_health_data_catalog.html`
3. Wait 5-10 minutes after push
4. Check Actions tab for errors

### Links Not Working?

1. Ensure all URLs start with `http://` or `https://`
2. Check for typos in href attributes
3. Verify external sites are online

### Search Not Working?

1. Clear browser cache
2. Check JavaScript console for errors
3. Ensure HTML structure hasn't changed
4. Test in different browser

## 💡 Tips

1. **Star Your Own Repo**: Helps others find it
2. **Watch Repository**: Get notified of issues
3. **Pin Repository**: Show on your profile
4. **Add README Badge**: Show license, status
5. **Create Release**: Tag v1.0.0 for official launch

## 📞 Need Help?

- [GitHub Docs](https://docs.github.com)
- [GitHub Community](https://github.community)
- [Git Guide](https://github.com/git-guides)

---

**Ready to launch? You've got this! 🚀**

---

*Questions? Open an issue or contact me directly.*
