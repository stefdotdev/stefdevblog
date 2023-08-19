---
title: "My First Blog Post"
pubDate: "2022-07-01"
description: "Welcome to my new blog about learning Astro! Here, I will share my learning journey as I build a new website."
author: "Astro Learner"
image:
  url: "https://docs.astro.build/assets/full-logo-light.png"
  alt: "The full Astro logo."
tags: ["Astro", "Learning In Public"]
---

## What I've accomplished

1. **Installing Astro**: First, I created a new Astro project and set up my online accounts.

2. **Making Pages**: I then learned how to make pages by creating new `.astro` files and placing them in the `src/pages/` folder.

3. **Making Blog Posts**: This is my first blog post! I now have Astro pages and Markdown posts!

## What's next

I will finish the Astro tutorial, and then keep adding more posts. Watch this space for more to come.

## **Code Example**

```js
import { getCollection, getEntry } from "astro:content";

// Get all entries from a collection.
// Requires the name of the collection as an argument.
// Example: retrieve `src/content/blog/**`
const allBlogPosts = await getCollection("blog");

// Get a single entry from a collection.
// Requires the name of the collection and either
// the entry `slug` (content collections) or `id` (data collections)
// Example: retrieve `src/content/authors/grace-hopper.json`
const graceHopperProfile = await getEntry("authors", "grace-hopper");
```
