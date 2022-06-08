## What is this
This's the "Kongqing's Lab" website project: [kql.ink](https://kql.ink) .  
This project are using:
- [HUGO](https://gohugo.io/)
- [Vercel](https://vercel.com/)

## Installation
To install `hugo` to you mac, you can simply use this command:
```bash
brew install hugo
```

Or check [this](https://gohugo.io/getting-started/installing/) to see other options.

## Usage
First, you need to clone this project with submodule:
```bash
git clone --recurse-submodules https://github.com/butterandfly/kql-hugo
```

Then go into the project folder and start the server:
```bash
cd kql-hugo
hugo server -D
```

In terminal it will give you the local url to vist.

## Using obsidian-blog-helper
Coming soon.

## Adding a post
Simply create a markdown file in `content/post` folder. Don't forget to add meta data by using frontmatter. Here is an example:
```markdown
---
title: "Hi!"
date: 2022-06-08
draft: false
cover:
  image: '/attachments/hi.jpg'
---

Today is June 9th!  
What a nice day!
```