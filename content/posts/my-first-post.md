---
title: "Hello Blog"
date: 2021-10-19T15:18:14-04:00
slug: 2021-10-19-my-first-post
type: posts
draft: false
categories:
  - blog
tags:
  - blog
---
I'm trying out Hugo!

I want to move away from my custom written blog and start using a standard static site generator instead.

My original blog was/is written in PHP and was backed by a dbm keystore as a database. I was enamored by the idea of the dbm based storage at the time. It felt like I was using very old technology for doing what was essentially NoSQL. Posts were stored as JSON file, and dynamically rendered. 

I also didn't want to deal with WYSIWYG editors, or any kind of frontend GUIs for editing the posts. So, I used a simple custom file format that contained a header with meta information like a title, data, and tags, a separator, and then hand written HTML. A PHP script would transform that file into a JSON file. A different script would load the JSON file into the database.

Hugo's file format is remarkably similar to the one I used! But Hugo has many obvious advantages over my workflow. No need for a database, or manually generating the JSON and loading. And of course, it just makes sense to avoid dynamically rendering pages that are all static anyway.
