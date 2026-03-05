# zachary-cunningham.github.io

Personal portfolio website for Zachary Cunningham, built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

**Live site:** [zachary-cunningham.github.io](https://zachary-cunningham.github.io)

## About

This is a static site that serves as a personal portfolio, showcasing projects and background information. It uses the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) Jekyll theme (dark skin, v4.24.0).

## Project Structure

```
.
├── _config.yml          # Jekyll site configuration and theme settings
├── _data/
│   ├── authors.yml      # Author profile (bio, avatar, social links)
│   └── navigation.yml   # Site navigation links
├── _includes/
│   └── footer.html      # Custom footer
├── assets/
│   ├── css/             # Custom stylesheets
│   └── images/          # Site images and screenshots
├── index.md             # Homepage content
├── Gemfile              # Ruby gem dependencies
└── CNAME                # Custom domain configuration
```

## Local Development

**Prerequisites:** Ruby and Bundler installed.

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

3. Open [http://localhost:4000](http://localhost:4000) in your browser.

## Deployment

The site is automatically deployed to GitHub Pages on every push to the main branch. The custom domain is configured via the `CNAME` file.

## Author

**Zachary Cunningham** — Learning full-stack software engineering.

- [GitHub](https://github.com/zachary-cunningham)
- [LinkedIn](https://www.linkedin.com/in/zachary-c-28412228b/)
