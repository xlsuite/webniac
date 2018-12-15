---
title: What is a webniac?
image: /images/welcome.jpg
imageMeta:
  attribution:
  attributionLink:
featured: true
author: ghost
date: Tue Jun 12 2018 18:59:59 GMT+0100 (IST)
tags:
  - getting-started
---

Hello hello, is this thing on? :)

### There are a few things that you should know up-front:

1. Ember Ghost is designed to be a static site version of the amazing [Ghost blogging platform](https://ghost.org/)

1. Ember Ghost is designed for developers who know how to deploy a satic site (folder of html files and assets) using something like S3 or even just on NGINX.

1. If you are slightly less tech savvy or if you want to manage your blog outside of just a set of files in a git repo we highly recommend signing up for [Ghost](https://ghost.org/pricing/)

### Quick Start

```sh
# if you don't have ember-cli installed already
npm install -g ember-cli

ember new super-blog
cd super-blog

ember install ember-ghost ember-ghost-casper-template
```

It will ask you if you want to update the `index.html` file and you should say yes 👍

If you want to see the blog system running on your local machine just run `npm start` and you will
be able to navigate to  [http://localhost:4200](http://localhost:4200) to see the blog in action.

---

The main thing you'll want to read about next is probably: [editing files with Ember Ghost](/the-editor/).

Once you're done reading, you can simply delete the default **Ghost** user from your team to remove all of these introductory posts!
