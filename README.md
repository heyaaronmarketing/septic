# Huntsville Window Washing Website

This repository contains a static website for **Huntsville Window Washing**, a fictional local window‑washing company used to demonstrate how to build an SEO‑friendly lead‑generation site. The site is built with [Jekyll](https://jekyllrb.com/), which makes it easy to generate blog posts, pages and a sitemap.

## Features

- **Local SEO focus** — Titles, meta descriptions and content are optimized for window washing in Huntsville, TX.
- **5+ pages** — Home, About, Services, Service Area, Contact and a Blog with daily posts.
- **Blog** — Includes seven sample posts published over a week to keep the site fresh and relevant.
- **Schema markup** — JSON‑LD for `LocalBusiness` included in the layout for better search engine understanding.
- **Sitemap and robots.txt** — Automatically generated sitemap and robots.txt file to help search engines crawl the site.
- **Easy configuration** — Business details, tracking IDs and contact information are stored in `_config.yml` so you can update them in one place.

## Getting started

1. Install Ruby and Jekyll if you don't already have them: `gem install jekyll bundler`.
2. Navigate into the project directory and run `bundle install` to install dependencies.
3. Build and serve the site locally with `bundle exec jekyll serve`.
4. Visit `http://localhost:4000` in your browser to see the site.

## Customization

* Update `_config.yml` with your business name, address, phone number and analytics IDs.
* Replace the placeholder form action in `contact.md` with your own form handler URL.
* Add or remove blog posts in the `_posts` directory as needed.
* Modify the CSS in `assets/css/styles.css` to adjust colors, fonts and layout.

## Deployment

You can deploy this site to GitHub Pages or any static hosting provider. For GitHub Pages:

1. Create a new repository on GitHub and push the contents of this project.
2. In the repository settings, enable GitHub Pages and choose the `main` branch as the source.
3. After a few minutes, your site will be live at `https://{username}.github.io/{repository}`.

For custom domains, configure DNS to point to your GitHub Pages site and update the `url` field in `_config.yml`.