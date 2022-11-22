---
title: Demo
slug: Demo
description: Description
date: 2022-11-21T21:52:18+08:00
lastmod: 2022-11-21T22:52:18+08:00
image: /images/banner.png
math: true
comments: true
categories:
  - Guide
  - Demo
tags:
  - Demo
  - Guide
  - Markdown
  - Syntax
  - Math
---

## Style

_Italic_

**Bold**

**_Italic Bold_**

~~Strikethrough~~

The <kbd>Ctrl</kbd> key on the keyboard

# H1

## H2

### H3

#### H4

##### H5

###### H6

## Paragraph

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## Code Block

### Normal code block

```js
function hi(delay) {
  return new Promise((resolve, reject) => {
    setTimeout(function () {
      console.log(delay);
      resolve();
    }, delay);
  });
}

async function f() {
  await hi(1000);
  await hi(3000);
  hi(2000);
  console.log(0);
}

f();
```

### Inline code block

use the `systemctl start docker` command to start the Docker

## Form

| Title   | Title   | Title   |
| ------- | ------- | ------- |
| Content | Content | Content |
| Content | Content | Content |
| Content | Content | Content |

## List

### Ordered list

1. Content
2. Content
3. Content

### Unordered list

- Content
- Content
- Content

### Nested list

- Content
  - Content
  - Content
- Content
  - Content
  - Content

## Math[^katex]

[^katex]: https://katex.org/docs/supported.html

$$
 \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
$$

## Quote

> Don't communicate by sharing memory, share memory by communicating.
>
> _[Rob Pike](https://www.youtube.com/watch?v=PAAkCSZUG1c)_

## Link

### Normal link

[Hugo](https://gohugo.io/)

### Hyperlinked image

[![](https://d33wubrfki0l68.cloudfront.net/c38c7334cc3f23585738e40334284fddcaf03d5e/2e17c/images/hugo-logo-wide.svg)](https://gohugo.io/)

### Footnote

Stack[^1]

[^1]: https://gohugo.io/

### Footnote link

[Hugo][a]

[a]: https://gohugo.io/

## Image

### Normal image

![](banner.png)

### Stories[^stories]

[^stories]: https://typlog.com/

![Photo by Florian Klauer on Unsplash](demo1.png) ![Photo by Luca Bravo on Unsplash](demo2.png)

![Photo by Helena Hertz on Unsplash](demo4.png) ![Photo by Hudai Gayiran on Unsplash](demo3.png)

## Video[^video]

[^video]: https://stack.jimmycai.com/writing/shortcodes

### Youtube

{{< youtube VIDEO_ID >}}
