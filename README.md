# 🍥DevRhylme Blog

A static blog template built with [Astro](https://astro.build) for **DevRhylme Foundation**.

[**🖥️ Live Demo**](https://www.devrhylme.org/)&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;

> README version: `2024-10-13`

![Preview Image](https://github.com/user-attachments/assets/7518ee27-75cc-4628-b9ee-66461ceca790)

## ✨ Features

- [x] Built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com)
- [x] Smooth animations and page transitions
- [x] Light / dark mode
- [x] Customizable theme colors & banner
- [x] Responsive design
- [ ] Comments
- [x] Search
- [ ] TOC (Table of Contents)

## 🚀 How to Use

1. [Generate a new repository](https://github.com/devrhylme/fuwari/generate) from this template or fork this repository.
2. To edit your blog locally, clone your repository, run `npm install` AND `npm install sharp` to install dependencies.
   - Install [Node.js](https://nodejs.org/en/download) if you haven’t already.
3. Edit the config file `src/config.ts` to customize your blog.
4. Run `npm run new-post <filename>` to create a new post and edit it in `src/content/posts/`.
5. Deploy your blog to Vercel, Netlify, GitHub Pages, etc. following [the Astro deployment guides](https://docs.astro.build/en/guides/deploy/). You need to edit the site configuration in `astro.config.mjs` before deployment.

## ⚙️ Frontmatter of Posts

```yaml
---
title: My First Blog Post
published: 2024-10-13
description: This is the first post of my new Astro blog for DevRhylme.
image: ./cover.jpg
tags: [AI, Web3, Python]
category: DevRhylme
draft: false
lang: en      # Set only if the post's language differs from the site's language in `config.ts`
---
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                            | Action                                           |
|:----------------------------------- |:-------------------------------------------------|
| `npm install` AND `npm install sharp` | Installs dependencies                            |
| `npm run dev`                       | Starts local dev server at `localhost:4321`      |
| `npm run build`                     | Builds your production site to `./dist/`         |
| `npm run preview`                   | Previews your build locally, before deploying    |
| `npm run new-post <filename>`       | Creates a new post                               |
| `npm astro ...`                     | Run CLI commands like `astro add`, `astro check` |
| `npm astro --help`                  | Get help using the Astro CLI                     |

<br>
Don't Forget to Give a ⭐