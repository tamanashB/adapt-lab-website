# ADAPT Lab Website

Website for the Bhattacharya Lab (Adaptive Dynamics Across Pathogen-host Transmission networks) at Washington University in St. Louis.

## Overview

This is a static site built with [Hugo](https://gohugo.io/) using the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme and deployed via GitHub Pages.

## Site Structure

- `content/` - Markdown files for all pages (Research, Publications, Team, Resources, Contact, Lab News)
- `static/images/` - All image files
- `layouts/` - Custom homepage layout
- `assets/css/extended/custom.css` - Custom styling (fonts, colors, backgrounds)
- `hugo.toml` - Hugo configuration and site settings
- `.github/workflows/deploy.yml` - GitHub Actions workflow for automatic deployment

## Customizations

- Custom homepage layout with profile image, welcome message, and Lab News section
- White background theme
- Increased navigation font sizes
- Hidden anchor link symbols on headings
- Password-protected lab resources (via Staticrypt)
- Custom CSS for WashU branding colors

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch. The GitHub Actions workflow builds the site with Hugo and publishes to the `gh-pages` branch.

## For Lab Members

Private lab resources are available in a separate [private repository](link-to-private-repo).

## Theme

[PaperMod](https://github.com/adityatelange/hugo-PaperMod) - A fast, clean, and responsive Hugo theme.
