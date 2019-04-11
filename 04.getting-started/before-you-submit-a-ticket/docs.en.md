---
title: 'Before You Submit A Ticket'
published: true
taxonomy:
    category:
        - docs
process:
    markdown: true
    twig: true
routable: true
cache_enable: true
visible: true
---

```
@font-face {
  font-family: Chunkfive; src: url('Chunkfive.otf');
}

body, .usertext {
  color: #F0F0F0; background: #600;
  font-family: Chunkfive, sans;
}

@import url(print.css);
@media print {
  a[href^=http]::after {
    content: attr(href)
  }
}
```