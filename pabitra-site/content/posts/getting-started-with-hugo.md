---
title: "Getting Started with Hugo"
description: "A quick guide to setting up your first Hugo website"
date: 2025-01-02
tldr: "Hugo makes building static sites fast and simple"
draft: false
tags: [hugo, tutorial, web]
toc: true
---

Hugo is one of the most popular static site generators. Here's a quick overview of why I chose it and how to get started.

## Why Hugo?

- **Speed**: Hugo builds sites incredibly fast
- **Simple**: No database, no server-side languages
- **Flexible**: Thousands of themes available
- **Free Hosting**: Works perfectly with GitHub Pages

## Basic Commands

Here are some essential Hugo commands:

```bash
# Create a new site
hugo new site mysite

# Create a new post
hugo new posts/my-first-post.md

# Start local server
hugo server -D

# Build the site
hugo
```

## Theme Setup

Adding a theme is straightforward:

```bash
cd themes
git clone https://github.com/athul/archie.git
```

Then update your `config.toml` to use the theme:

```toml
theme = "archie"
```

That's it! You're ready to start blogging.

## Conclusion

Hugo combined with the Archie theme gives you a beautiful, minimal blog with zero hassle. Give it a try!
