---
title: 'Mettre à jour un dépôt avec un `.gitignore` actualisé.'
date: 2026-02-02
permalink: /posts/2012/08/blog-post-4/
tags:
  - cool posts
  - category1
  - category2
---

Sur un dépôt à jour:
```
git add .gitignore
git commit -m "Update gitignore"
git rm -r --cached .
git add .
git commit -m "Update files wrt gitignore"
```

Source: [https://stackoverflow.com/a/38451183](https://stackoverflow.com/a/38451183).
