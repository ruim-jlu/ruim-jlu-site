<p align="center"><a href="https://wowchemy.com/templates/" target="_blank" rel="noopener"><img src="https://wowchemy.com/uploads/readmes/academic_logo_200px.png" alt="Hugo Academic Template for Wowchemy Website Builder"></a></p>

# Academic Template for [Hugo](https://github.com/gohugoio/hugo)

## Deployment Guide

### 1. Hugo Installation (Windows)

1. **Download Hugo**: Visit [Hugo v0.90.0-DD0D3FDB+extended releases](https://github.com/gohugoio/hugo/releases/tag/v0.90.0-DD0D3FDB+extended)
2. **Download**: `hugo_extended_0.90.0_Windows-64bit.zip`
3. **Extract**: Unzip to `C:\Users\[username]\hugo-0.90.0\`
4. **Set PATH**: Add `C:\Users\[username]\hugo-0.90.0` to system PATH environment variable
5. **Verify**: Open new terminal and run `hugo version`

### 2. Local Development

```bash
# Clone repository
git clone <repository-url>
cd ruim-jlu-site

# Start local server for development
hugo server -D
# Visit http://localhost:1313
```

### 3. Build & Deploy

```bash
# Build static site
hugo

# The built site will be in public/ directory
# Deploy public/ contents to your web server
```

#### Deploy to GitHub Pages

**Current Project Configuration:**
```bash
# Build the site
hugo

# Navigate to public directory
cd public

# Check current status
git status

# Add all changes
git add .

# Commit changes
git commit -m "Update website - $(date '+%Y-%m-%d %H:%M:%S')"

# Push to remote repository (ruim-jlu.github.io)
git push origin master
```

**Repository Information:**
- Remote repository: `git@github.com:ruim-jlu/ruim-jlu.github.io.git`
- Branch: `master`
- Website URL: `https://ruim-jlu.github.io`

**Setup for First Time (if needed):**
```bash
cd public
git init
git remote add origin git@github.com:ruim-jlu/ruim-jlu.github.io.git
git add .
git commit -m "Initial commit"
git push -u origin master
```

**Note**: The public directory is already configured as a separate git repository pointing to the GitHub Pages repository.

### 4. Troubleshooting

- **Hugo command not found**: Ensure PATH is set correctly and restart terminal
- **Port already in use**: Use `hugo server -D --port 1314`
- **Build errors**: Check Hugo version compatibility (requires v0.90.0+ extended)

## About

The Hugo **Academic Resumé Template** empowers you to create your job-winning online resumé and showcase your academic publications.

[Check out the latest demo](https://academic-demo.netlify.app/) of what you'll get in less than 10 minutes, or [view the showcase](https://wowchemy.com/user-stories/).

[**Wowchemy**](https://wowchemy.com) makes it easy to create a beautiful website for free. Edit your site in Markdown, Jupyter, or RStudio (via Blogdown), generate it with Hugo, and deploy with GitHub or Netlify. Customize anything on your site with widgets, themes, and language packs.

- 👉 [**Get Started**](https://wowchemy.com/templates/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=(%23MadeWithWowchemy%20OR%20%23MadeWithAcademic)&src=typed_query)
- 💡 [Request a **feature** or report a **bug** for _Wowchemy_](https://github.com/wowchemy/wowchemy-hugo-modules/issues)
- ⬆️ **Updating Wowchemy?** View the [Update Guide](https://wowchemy.com/docs/guide/update/) and [Release Notes](https://wowchemy.com/updates/)

## Crowd-funded open-source software

To help us develop this template and software sustainably under the MIT license, we ask all individuals and businesses that use it to help support its ongoing maintenance and development via sponsorship.

### [❤️ Click here to unlock rewards with sponsorship](https://wowchemy.com/plans/)

## Ecosystem

* **[Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli):** Automatically import publications from BibTeX

[![Screenshot](https://raw.githubusercontent.com/wowchemy/wowchemy-hugo-modules/main/academic.png)](https://wowchemy.com)

## Demo image credits

- [Open book](https://unsplash.com/photos/J4kK8b9Fgj8)
- [Course](https://unsplash.com/photos/JKUTrJ4vK00)

## Latest news
<!--START_SECTION:news-->
* [What&#39;s new in v5.2?](https:&#x2F;&#x2F;wowchemy.com&#x2F;blog&#x2F;v5.2.0&#x2F;)
* [What&#39;s new in v5.1?](https:&#x2F;&#x2F;wowchemy.com&#x2F;blog&#x2F;v5.1.0&#x2F;)
* [Version 5.0 (February 2021)](https:&#x2F;&#x2F;wowchemy.com&#x2F;blog&#x2F;v5.0.0&#x2F;)
* [Version 5.0 Beta 3 (February 2021)](https:&#x2F;&#x2F;wowchemy.com&#x2F;blog&#x2F;v5.0.0-beta.3&#x2F;)
* [Version 5.0 Beta 2 (January 2021)](https:&#x2F;&#x2F;wowchemy.com&#x2F;blog&#x2F;v5.0.0-beta.2&#x2F;)
<!--END_SECTION:news-->

[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/starter-academic/readme?pixel)](https://github.com/igrigorik/ga-beacon)
