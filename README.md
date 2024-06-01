# yogeshingale

This repository contains the source code for my personal portfolio website. The website is built using [Hugo](https://gohugo.io/), a static site generator written in Go, and is hosted on Amazon S3 with Cloudflare as the CDN.

## Project Structure

The main directories in this project are:

- `content`: Contains the Markdown files for the website's pages.
- `data`: Contains YAML files used to generate certain parts of the website.
- `static`: Contains static files such as images.
- `themes`: Contains the Hugo theme used for the website.

## Local Setup

Follow these steps to set up the project locally:

1. **Clone this repository**
```bash
git clone git@github.com:yogingale/yogeshingale.git
```

2. **Install Hugo**
If you're on macOS, you can use Homebrew:
```bash
brew install hugo
```
For other operating systems, see the [official Hugo documentation](https://gohugo.io/installation/).

3. **Start the Hugo server**
```bash
hugo server
```

4. **View the website**
Open your web browser and go to `http://localhost:1313`.

## Customization
You can customize the website by editing the files in the `content`, `data`, and `static` directories. Here are some examples:

- To edit the homepage, modify `content/_index.md`.
- To add a blog post, create a new Markdown file in `content/post/`.
- To add a portfolio project, add a new entry to `data/portfolio.yml`.
- To change the about page, edit `content/about.md`.
- To add an image, put it in `static/images`.

## Deployment
This website is deployed using a GitHub Action that builds the Hugo site and uploads the static files to an Amazon S3 bucket. See .github/workflows/main.yml for the workflow configuration.

## Acknowledgments
Special thanks to the developers of the following projects:

[Hugo](https://gohugo.io/) - The static site generator used for this project.
[Anatole theme](https://github.com/lxndrblz/anatole) - The beautiful theme that gives this site its clean and modern look.
