This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
"# kylike" 
## Add Blog Post

1. Create a Markdown file in the `_posts` folder.
2. The filename should follow the format `YYYY-MM-DD-title.md`. For example: `2008-12-01-hello-world.md`.
3. Include front matter at the beginning of the file. This metadata defines the post's layout, title, date, categories, and a short teaser.
	Use the following format:
```yaml
---
layout: page
title: "My 'Hello, World!"
date: 2008-12-01
categories: [  ASP.NET, WinForms]
teaser: "Since this is the first post in a programming blog I think a Hello World program in Winforms and ASP.NET is a good idea."
---
```

4. Write your post content below the front matter using Markdown or HTML.

## Add Project

### Web Application
1. Add the Project to the projects.yml File inside _data directory.
2. Use the following format to add a new project to the list:
```yaml
- title: "StatsDen"
  url: 'https://statsden.com/'
  image: '/images/statsden.png'
  text: 'Tool for gathering technical information on websites'
```



### old projects
1. Create a Markdown file in the `_oldprojects` folder.
2. The filename should follow the format `title.md`. 
3. Include front matter at the beginning of the file. This metadata defines the projects layout, title, website_title, file, website_link,description,header,permalink .
	Use the following format:
```yaml
---
layout              : project
title               : "MoviePlay"
website_title       : "Website"
description: "Open source movie library application for Windows"
header:
  image_fullwidth: header_unsplash_12.jpg
permalink           : "/oldprojects/movieplay/"
---
```
4. Write your post content below the front matter using Markdown or HTML.

### tools
1. Create a Markdown file in the `_tools` folder.
2. The filename should follow the format `title.md`. 
3. Include front matter at the beginning of the file. This metadata defines the projects layout, title,description,header,permalink . For github_title and github_link, they are optional, so you can include them only if needed.
	Use the following format:
```yaml
---
layout              : project
title               : "antpoolmon"
description: "Command-line script for monitoring an AntPool account"
header:
  image_fullwidth: header_unsplash_12.jpg
github_title: "GitHub"  # Optional
github_link: "https://github.com/amgedr/"  # Optional
permalink           : "/tools/antpoolmon/"
---
```

4. Write your post content below the front matter using Markdown or HTML.

## Reorder the Projects on the Homepage:
- Web Applications projects should remain in the same order as they are written in the code.
- The Tools and Old Projects sections should be sorted alphabetically
