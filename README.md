# NF-FixX Blog

This is a technical blog build by NF-FixX team.

## Getting Started

First, install the dependencies:

```sh
npm install
```

## Development

To start the development server:

```sh
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Building the Project

To build the project:

```sh
npm run build
```

## Running the Project

To start the project:

```sh
npm run start
```

## Adding a Post

Posts are written in Markdown and stored in the [`posts`](command:_github.copilot.openRelativePath?%5B%22posts%22%5D "posts") directory. To add a new post:

1. Create a new Markdown file in the [`posts`](command:_github.copilot.openRelativePath?%5B%22posts%22%5D "posts") directory.
2. The filename should be the slug of your post (e.g., `my-new-post.md`).
3. At the top of the file, include the frontmatter. This is metadata about the post and should be written in YAML. Here's an example:

```markdown
---
title: "My New Post"
date: "2022-01-01"
tags: ["tag1", "tag2"]
---
```

4. Below the frontmatter, write the content of your post in Markdown.

After adding the post, it will automatically appear on the blog page when you run the project.
