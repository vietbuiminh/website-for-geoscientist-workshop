# Getting Started

## Demo
[![Demo](template.png)](https://vietmbui.com/force-academic-mk/)
Follow these steps to set up your own website using this template:

## 1. Fork the Repository

- Go to the [force-academic-mk repository page](https://github.com/vietbuiminh/force-academic-mk).
- Click **Fork** at the top right.
- Name your new repository as `yourusername.github.io`.

![Fork repository](fork.gif "segment")

## 2. Edit Configuration

- In your forked repository, locate the `config.yml` file.
- Update the settings as needed (e.g., site title, description, author).

### _data/authors.yml



### Markdown file

The front matter is a block of YAML metadata placed at the top of a Markdown file, enclosed by triple dashes (`---`). It defines page-specific variables such as title, layout, author, categories, tags, and more. For the Minimal Mistakes theme, a typical front matter might look like:

```yaml
---
title: "Getting Started"
layout: single
author: vietbui
categories: [workshop]
tags: [setup, guide]
---
```

This information helps Jekyll and the Minimal Mistakes theme render the page correctly and organize content across the site.

> **Tip:** Inside the template, the main fields you may want to modify in the front matter are:
> - `title`
> - `overlay_image`
> - `author`
> - `categories`
> - `tags`
> 
> Adjust these values to personalize your site’s pages and appearance.

![Front Matter inside the project](frontmatter.png)

## 3. Create the `gh-pages` Branch

- Go to the **Code** tab.
- Click **Branch: main** and type `gh-pages` to create a new branch.
- Switch to the `gh-pages` branch.

![Creating new branch gh-pages](gh-pages.gif "segment")

## 4. Enable GitHub Pages

- Go to **Settings** > **Pages**.
- Under **Source**, select the `gh-pages` branch.
- Click **Save**.



Your site will be published at `https://yourusername.github.io` shortly.

## 5. Final Notes
> One of the key benefits of using this template is its responsive website design. All components are optimized for viewing on different screen sizes and aspect ratios, ensuring your site looks great and functions smoothly on desktops, tablets, and mobile devices. This adaptability provides a consistent user experience and makes your content accessible to a wider audience.

![Responsive design in action](responsive.gif "segment")