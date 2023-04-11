---
title: "Getting started with hugo"
date: 2023-04-11T11:24:09+02:00
description: "A Quick Guide"
tags: ["programming"]
# add toc to the page
tableOfContents: true
#tocLevels: "3"
draft: false
---

## Hugo Quick Start Guide for Personal Projects

Welcome to my Hugo site! This document is just to help me understand the basic structure of Hugo and provide me with some tips and tricks for using the platform to document my personal projects.

---

## Folder Structure

The basic folder structure for a Hugo website looks like this:

```
├── archetypes/
├── content/
│   ├── docs/
│   ├── posts/
│   └── projects/
├── data/
├── layouts/
├── static/
├── themes/
├── config.toml
└── README.md
```

Where the folders and files are:
* The `archetypes/` folder contains templates for creating new content.
* The `content/` folder contains all of the content for your website, including `docs/`, `posts/`, and `projects/`.
* The `data/` folder is used for storing data files, such as .json, .yml, and .csv.
* The `layouts/` folder contains the templates for your website.
* The `static/` folder contains any static files, such as images, that you want to include in your website.
* The `themes/` folder contains any themes you`ve installed.
* The `config.yml` file is used to configure your Hugo website.
* The `README.md` file is an optional file that can be used to provide documentation for your website.

---

## Posting Content

To post content on your Hugo website, you can use the `hugo new` command. For example:

``` 
hugo new posts/my-first-post.md 
```

This will create a new file in the `content/posts/` directory with the name `my-first-post.md`. You can then edit this file to add your content.

You can also use the hugo new command to create new pages in the `content/docs/` directory or new project pages in the `content/projects/` directory.

---

## Tips & Tricks

* Use the `--gc` flag when running `hugo` to clean up any generated files that are no longer needed.

* Use the `--minify` flag when running `hugo` to minify your HTML, CSS, and JavaScript files for faster loading times.

* Use the `--watch` flag when running `hugo` to automatically rebuild your website when changes are made.

* Use the `--buildDrafts` flag when running `hugo` to include draft posts in your website.

* Use the `--disableFastRender` flag when running `hugo` to disable fast rendering, which can sometimes cause issues when making changes to your templates.

* Use the `--ignoreCache` flag when running `hugo` to ignore any cached data and force Hugo to rebuild everything.

---

## Useful Links

If you have any questions, be sure to check out the [Hugo documentation](https://gohugo.io/documentation/) or the [Hugo forums](https://discourse.gohugo.io) for more information. Happy building!

