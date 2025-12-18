# Pabitra Chowdhury - Personal Blog

A minimal personal blog built with [Hugo](https://gohugo.io/) and the [Archie theme](https://github.com/athul/archie).

## Quick Setup

### 1. Create GitHub Repository

Create a new repository named `pabitrachowdhury.github.io` (replace with your GitHub username).

### 2. Clone and Setup

```bash
# Clone your new repository
git clone https://github.com/pabitrachowdhury/pabitrachowdhury.github.io.git
cd pabitrachowdhury.github.io

# Copy all files from this project into the repository
# Then add the Archie theme as a submodule
git submodule add https://github.com/athul/archie.git themes/archie
git submodule update --init --recursive
```

### 3. Configure GitHub Pages

1. Go to your repository **Settings**
2. Navigate to **Pages** in the sidebar
3. Under **Build and deployment**, select:
   - Source: **GitHub Actions**

### 4. Push and Deploy

```bash
git add .
git commit -m "Initial commit with Hugo + Archie theme"
git push origin main
```

The GitHub Action will automatically build and deploy your site!

Your site will be live at: `https://pabitrachowdhury.github.io`

## Local Development

```bash
# Install Hugo first: https://gohugo.io/installation/

# Initialize submodules (if not done)
git submodule update --init --recursive

# Run local server with drafts
hugo server -D

# Create new post
hugo new posts/my-new-post.md

# Build for production
hugo
```

## Customization

### config.toml Options

- `title`: Your site title
- `subtitle`: Tagline shown on homepage
- `mode`: Theme mode - `light`, `dark`, `toggle`, or `auto`
- `params.social`: Add/remove social links
- `menu.main`: Customize navigation menu

### Writing Posts

Create posts in `content/posts/` with this frontmatter:

```yaml
---
title: "Post Title"
description: "Brief description"
date: 2025-01-01
tldr: "Quick summary (optional)"
draft: false
tags: [tag1, tag2]
toc: true # Table of contents (optional)
---
```

## Theme Features

- Auto dark/light mode based on system preference
- Clean, minimal design
- Syntax highlighting for code
- Tags support
- Table of contents
- Responsive design

## License

Content © Pabitra Chowdhury  
[Archie Theme](https://github.com/athul/archie) - MIT License
