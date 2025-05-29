---
title: "Building My Blog with Hugo: The Process Behind the Posts"
date: 2025-05-29T10:00:00+01:00
draft: false
description: "Reflections on how I set up my portfolio with Hugo, the theme I used, and what it’s like writing and publishing blog posts."
tags: ["Hugo", "Static Site", "Blogging", "Web Development", "Portfolio"]
categories: ["Personal Projects"]
---

![Hugo banner](images/blog/2025-05-29-hugo.jpg)

Writing a blog post might sound daunting at first, but using Hugo as a static site generator makes the process surprisingly smooth — once you’ve got the basics set up.

In Hugo, each blog post is just a Markdown file with some front matter (metadata like title, date, tags, etc.). Once you get used to that format, writing posts becomes as simple as opening your favorite text editor, typing out your content, and saving the file in the right folder.

### Pros of Writing with Hugo
- **Full control** over structure and formatting
- Markdown is clean, portable, and distraction-free
- No database or backend to worry about
- Instant feedback when running locally

### Challenges
- You do need to understand the Hugo folder structure and basic front matter syntax
- There’s no WYSIWYG editor — previewing your work requires running a local server
- If your theme has custom features, you may need to look at its docs or source to take full advantage

That said, once you've written a few posts, the process becomes fast and efficient. I find it easier than using bulky CMS systems like WordPress — and the end result is lightweight and super fast.

## My Hugo Site Setup

To build my blog and portfolio site, I used the [**Hugo static site generator**](https://gohugo.io/) with the following components:

### Theme: [Adritian by Zetxek](https://github.com/zetxek/adritian-free-hugo-theme)
The **Adritian** theme is a clean, responsive, and developer-friendly theme that supports:
- Personal branding (CV/resume layout)
- Blog posts
- Portfolio/project sections
- Tagging and categorization
- Multilingual support

I made a few custom tweaks to better match my style and structure, but overall, the theme was easy to work with and well-documented.

## Infrastructure

Here’s how I host and manage the whole site:

- **Local Development**: I write and preview content on my local machine using the `hugo server` command.
- **Version Control**: Everything (content, config, theme) is tracked with Git.
- **Deployment**:
  - **Hosting**: The site is deployed as a static site, which means it can run anywhere. I chose to host it using [GitHub Pages](https://pages.github.com/) (or optionally a VPS or Netlify — pick your flavor).
  - **Build Automation**: On push to the `main` branch, GitHub Actions rebuilds the site and pushes it live.

This gives me a simple yet powerful setup where I can:
- Write posts in Markdown
- Commit changes to Git
- Let automation handle the publishing

## Final Thoughts

Writing blog posts with Hugo has been a rewarding experience. It keeps me writing consistently, and it gave me full ownership of my digital portfolio. While there’s a learning curve at first, especially around Hugo’s templating and folder structure, the payoff is worth it.

If you’re looking for a fast, minimalist, developer-friendly blogging platform — Hugo is hard to beat.
