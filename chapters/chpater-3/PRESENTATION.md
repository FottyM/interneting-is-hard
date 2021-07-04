---
marp: true
theme: uncover
class: invert
paginate: true
footer: 'https://github.com/FottyM/interneting-is-hard'
---
<!--
_paginate: false
-->
# ***Internting is hard in 20201***

_Fortunat Mutunda_


***_[Interneting is hard &copy;2021](https://www.internetingishard.com/)_***

---
<!--
_paginate: false
-->
### ***CHAPTER 3***
##### _Links and Images_

---
# ***Introduction***
Links point the user to a different HTML document, and images pull another resource into the page.

![Links and images](./assets/links-and-images.png)

___
# ***Anchors***
Link are represented by the anchor element `<a>`
```html
<p>This example is about links and <a>images</a>hello</p>
```
___
# ***Attributes***
In the same way that an element adds meaning to the content it contains, an HTML “[attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)” adds meaning to the element it’s attached to.
```html
<p>This example is about links and <a href="link.html">images</a>hello</p>
```

___

![attributes](./assets/html-attributes.png)
___

# ***Links paths***
- Absolute
- Relative
- Root-relative 

---

![paths](./assets/absolute-relative-root-relative-links.png)

---
```html
<!-- -->
<body>
    <a href="my-relative-page.html">Relative Page</a>
    <a href="http://absolutepage.com">Some absolute page</a>
    <a href="/">Root relative</a>
</body>
<!--  -->
```
---
# ***Link targets***
- __self:_ the current browsing context. (Default)
- __blank:_ usually a new tab, but users can configure browsers to open a new window instead.
- __parent:_ the parent browsing context of the current one. If no parent, behaves as _self.
- __top:_ the topmost browsing context (the "highest" context that’s an ancestor of the current one). If no ancestors, behaves as _self.
[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)

---
# ***Images***
Images use the self-closing HTML tag img
`<img src='my-image.png'/>`
- src(source) attribute would specify the path of the image.
---
# ***Image Formats***
- JPG
- PNG
- GIF
- SVG
---
# ***Image Formats: JPG(JPEG)***

JPG images are designed for handling large color palettes without exorbitantly increasing file size.
i.e., photos, landscapes etc...

---
# ***Image Formats: GIF***

GIFs are the go-to option for simple animations, but the trade off is that they’re somewhat limited in terms of color palette—never use them for photos.

---
# ***Image Formats: PNG***

PNGs are great for anything that’s not a photo or animated. For photos, a PNG file of the same quality (as perceived the human eye) would generally be bigger than an equivalent JPG file.

---
# ***Image Formats: SVG***

Unlike the pixel-based image formats above, SVG is a vector-based graphics format, meaning it can scale up or down to any dimension without loss of quality. This property makes SVG images a wonderful tool for responsive design. They’re good for pretty much all the same use cases as PNGs, and you should use them whenever you can.

---
