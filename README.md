# Console 84

A developer portfolio and microblog built with Jekyll, showcasing projects, thoughts, and technical explorations.

## About

**Console 84** is the personal portfolio site of Alfredo Saavedra, a developer passionate about JavaScript and computer science. This site serves as a platform for sharing technical articles, project showcases, and development insights.

## Tech Stack

- **Framework**: Jekyll (Static Site Generator)
- **Theme**: Trophy (customized)
- **Styling**: Sass
- **JavaScript**: Vanilla JS with Rellax and WOW.js for animations
- **External Libraries**:
  - Google Fonts
  - Font Awesome
  - Normalize.CSS

## Site Structure

```
.
├── _posts/           # Blog posts in Markdown
├── _layouts/         # Jekyll layout templates
├── _includes/        # Reusable template components
├── _sass/            # Sass stylesheets
├── assets/           # Static assets (JS, CSS, images)
├── _config.yml       # Site configuration
├── index.html        # Homepage with post listings
└── archive.html      # Archive page for all posts
```

## Local Development

### Prerequisites
- Ruby (version 2.5 or higher recommended)
- Bundler (`gem install bundler`)

### Setup
1. Clone the repository
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```
4. Visit `http://localhost:4000` in your browser

### Creating New Posts

Create a new markdown file in `_posts/` following the naming convention: `YYYY-MM-DD-post-title.md`

Example front matter:
```yaml
---
layout: post
title: "Your Post Title"
date: 2025-01-15
categories:
  - JavaScript
  - Web Development
description: "Brief description for SEO"
image: /path/to/featured-image.jpg
image-sm: /path/to/thumbnail.jpg
---
```

## Configuration

Key settings in `_config.yml`:
- **Site Title**: Console 84
- **Description**: A sexy developer microblog
- **Email**: alfsaav@gmail.com
- **Pagination**: 5 posts per page

## Current Status

This site is currently undergoing updates and improvements for 2025. See [ROADMAP.md](ROADMAP.md) for planned enhancements.

## License

Theme originally based on Trophy Jekyll theme (MIT License).
