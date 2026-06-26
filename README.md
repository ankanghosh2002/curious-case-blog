# The Curious Case of Ankan Ghosh??

A cosmic personal journal, digital garden, and personal blog by **Ankan Ghosh**.

**The Curious Case of Ankan Ghosh??** is designed like a strange old-web personal journal where curiosity, space, astronaut stories, opinions, personal notes, and fictional fragments come together. The website has a mysterious, cinematic, slightly weird personality — like the reader is entering a personal case file from the mind of someone curious about life, science, stories, and the universe.

---

## Live Website

Live URL:

```txt
https://curiouscaseofankan.netlify.app/
---

## Project Overview

This project is built as a personal blog using:

* **Astro** for static site generation
* **Markdown** for blog posts
* **Decap CMS** for writing and editing posts from `/admin/`
* **Netlify** for free hosting
* **GitHub** for version control and CMS content storage

The goal of this project is to allow the author to write and publish blog posts without manually entering the codebase every time.

---

## Main Concept

The blog is designed as a:

```txt
cosmic personal journal
+
old-web digital garden
+
personal case file
+
space and curiosity archive
```

The visual style is inspired by old personal websites, literary blogs, narrow layouts, paper-like backgrounds, red ink accents, serif typography, ornamental details, and mysterious personal writing.

---

## Main Sections

The website contains the following main pages:

```txt
/
 /curiosity/
 /space/
 /stories/
 /about/
 /contact/
 /dont-click-here/
 /admin/
```

### Admin

The Decap CMS dashboard where new blog posts can be created and edited.

---

## Features

* Fully custom personal blog design
* SEO-friendly separate pages
* Blog posts generated from Markdown files
* Dynamic blog post pages using Astro routing
* Category pages for Curiosity, Space, and Stories
* Popular posts support
* Cover image support
* Markdown image support
* Decap CMS admin panel
* Netlify-ready deployment
* Free hosting using Netlify
* Responsive mobile-friendly design
* Old-web inspired narrow layout
* Custom masthead logo
* Page banner images for category pages
* Hidden “Don’t Click Here” page
* Share/copy homepage link feature

---

## Tech Stack

```txt
Astro
HTML
CSS
Markdown
Decap CMS
Netlify
GitHub
```

---

## Folder Structure

```txt
curious-case/
│
├── public/
│   ├── admin/
│   │   ├── index.html
│   │   └── config.yml
│   │
│   ├── banners/
│   │   ├── about-banner.png
│   │   ├── curiosity-banner.png
│   │   ├── space-banner.png
│   │   └── stories-banner.png
│   │
│   ├── uploads/
│   │   └── whyicreatedccag.png
│   │
│   ├── ccag-logo.png
│   ├── ccag-icon.ico
│   └── dontclickhere.png
│
├── src/
│   ├── content/
│   │   └── blog/
│   │       └── why-i-created-the-curious-case.md
│   │
│   ├── layouts/
│   │   └── BaseLayout.astro
│   │
│   ├── pages/
│   │   ├── index.astro
│   │   ├── curiosity.astro
│   │   ├── space.astro
│   │   ├── stories.astro
│   │   ├── about.astro
│   │   ├── dont-click-here.astro
│   │   └── blog/
│   │       └── [slug].astro
│   │
│   ├── styles/
│   │   └── global.css
│   │
│   └── content.config.ts
│
├── astro.config.mjs
├── package.json
├── package-lock.json
└── README.md
```

## Blog Post Format

Each blog post is a Markdown file with frontmatter.

Example:

```md
---
title: "Why I Created The Curious Case of Ankan Ghosh??"
description: "A note about personal websites, strange thoughts, space, and why I wanted my own corner of the internet."
pubDate: 2026-06-26
category: "curiosity"
popular: true
draft: false
cover: "/uploads/whyicreatedccag.png"
---

The internet is crowded with social media profiles, portfolios, and perfectly curated online identities.

But I wanted something different — a place that felt personal, unfiltered, and genuinely mine.

That's how **The Curious Case of Ankan Ghosh** came to life.
```

## Adding Images in Markdown

Images uploaded through Decap CMS are stored in:

```txt
public/uploads/
```

They can be used in Markdown like this:

```md
![Image description](/uploads/image-name.png)
```

Example:

```md
![Young Ankan looking into destiny](/uploads/young-ankan.png)
```

---

## Layout

The global layout is stored in:

```txt
src/layouts/BaseLayout.astro
```

This layout contains:

* HTML head
* SEO meta tags
* Global CSS import
* Navbar
* Footer
* Netlify Identity script if used

---

## Global Styles

The main CSS file is:

```txt
src/styles/global.css
```

This file contains:

* Root color variables
* Typography
* Layout styles
* Navbar styles
* Masthead styles
* Blog post styles
* Category page banner styles
* Secret page styles
* Share section styles
* Responsive styles

---

## Design System

### Main Colors

```css
--paper: #faf7ee;
--paper-deep: #efe4cd;
--ink: #2c251d;
--muted: #746b62;
--faint: #d9cdb9;
--red-ink: #901714;
--space-blue: #191d4f;
--star-gold: #b88a35;
```

### Main Style Direction

```txt
old web
personal journal
cosmic notebook
narrow centered layout
serif typography
red ink accent
paper background
mysterious case-file feeling
```

---

## Updating the Website

After making code changes locally:

```bash
git status
git add .
git commit -m "Describe your change"
git push
```

After pushing, GitHub updates and Netlify automatically rebuilds the live site.

---

## Future Improvements

Possible future upgrades:

* Add search page
* Add RSS feed
* Add sitemap
* Add tags
* Add related posts
* Add reading time
* Add dark mode
* Add post pagination
* Add Open Graph image generation
* Add newsletter signup
* Add comments or webmentions
* Add custom domain
* Add analytics
* Add better CMS preview styling

---

## License

This is a personal project. All writing, branding, and visual assets belong to Ankan Ghosh unless otherwise stated.

For public reuse, please ask for permission before copying the design, content, or assets.

---

## Final Note

This website is not meant to be perfect.

It is meant to feel alive, personal, unfinished, strange, curious, and human.

A small corner of the internet where thoughts can orbit freely.
