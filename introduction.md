---
title: Introduction
seoTitle: title for search engines
seoDescription: description for search engines
isFree: true
---

Many people know theory, syntax, did exercises or followed tutorials, even played with boilerplate.

You can easily find reference material to learn the syntax and rules of a particular language or framework.

```
server.get('/books/:bookSlug/:chapterSlug', (req, res) => {
  const { bookSlug, chapterSlug } = req.params;
  app.render(req, res, '/public/read-chapter', { bookSlug, chapterSlug });
});
```
