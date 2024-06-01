---
title: 'Portfolio Site'
date: 2024-05-01T21:47:41+00:00
draft: false
tags:
  - Hugo
  - Portfolio
  - GitHub Actions
  - Amazon S3
  - Cloudflare
  - DevOps
  - Web Development
  - Static Site Generator
thumbnail: "images/portfolio-blog2.png"
---

# How I Created My Portfolio Website
Welcome to my blog post! Today, I'll be sharing the process I used to create my portfolio website. I'm DevOps Engineer and I wanted a simple, clean, and responsive website to showcase my work, projects, and blog posts. I want to focus more on content and less on front end. 

This guide covers everything from choosing a front-end framework to deploying and hosting the site. Let's get started!

## Choosing the Framework
I chose [Hugo](https://gohugo.io/getting-started/quick-start/), a fast and flexible static site generator, for my portfolio website. Hugo is written in Go and is known for its speed, flexibility, and ease of use. For the theme, I went with [Anatole](https://anatole-demo.netlify.app/post/image-test/). It's a clean, simple, and responsive theme that perfectly suited my needs. You can find the theme in the themes/anatole directory of my project.

Later in this blog post, I'll give steps on how you can setup same site for your portfolio.

## Setting Up the Repository
The entire code for my website is hosted on my [GitHub repository](https://github.com/yogingale/yogeshingale). This allows me to keep track of all changes and makes it easy for others to use my code as a starting point for their own portfolio website. Follow the [README file](https://github.com/yogingale/yogeshingale) in the repository to setup the site locally.

## Deploying the Site
I used GitHub Actions to automate the deployment of my website. Whenever I push changes to the repository, a GitHub Action builds the Hugo site and deploys the static files to an Amazon S3 bucket. You can find the workflow file for this action in the `.github/workflows` directory of my repository.

## Hosting the Website
I bought my domain from Namecheap. They offer a wide selection of domain names at affordable prices, and their customer service is top-notch.

After purchasing the domain, I used Cloudflare to host the website. Cloudflare provides a global CDN, shared SSL certificates, and I can easily manage my DNS records through their dashboard.

## What's Next?
In the future, I plan to add more blog posts related to DevOps, SRE, Kubernetes, Python, and more. Stay tuned!
