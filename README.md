# blog-legacy-web-code (archived)

> **This is the original source code for [playingaws.com](https://www.playingaws.com), an AWS-focused technical blog.**
>
> The blog has been migrated to a new private codebase. This repository is kept for historical reference and is no longer actively maintained. No new posts or features will be added here.
>
> The archived version is still accessible at: **[d3oyszvjcdgtwm.cloudfront.net](https://d3oyszvjcdgtwm.cloudfront.net)**

---

## About this project

This repository contains the Jekyll source code used to build and run the Playing AWS blog from its launch until the migration to a new private codebase.

**Stack:**

- **Jekyll** with the [Chirpy theme](https://github.com/cotes2333/jekyll-theme-chirpy) — static site generator
- **Multi-language** — posts in both English and Spanish (`_posts/en/`, `_posts/es/`)
- **AWS backend** — contact and feedback forms backed by AWS Lambda, Step Functions, and SES
- **Google Analytics** and **Giscus** for comments

## Run it locally

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

## Want to interact with the current blog?

The live blog is at **[playingaws.com](https://www.playingaws.com)**. To report a bug, suggest content, or start a discussion, use the public community repository:

**[github.com/alazaroc/blog-web-code-community](https://github.com/alazaroc/blog-web-code-community)**

There you can:

- 🐛 **Report a bug** — something broken or behaving unexpectedly on the blog
- 💡 **Request a feature** — UX improvements, new sections, accessibility, performance
- 📝 **Request content** — a topic, an AWS service deep-dive, or a tutorial series
- 💬 **Start a discussion** — general AWS questions, feedback, or comments on a post
