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
### ***CHAPTER 2***
##### _Hello HTML!_

---
# ***Structure of a web page***
HTML is pages are build with _html_ tags, with each having an opening tag and a closing tag, with few exception having a self closing tag.
___

# ***<p> Tags </p>***
```html
<p>Hello Html</p> 
```
An opening tag has one opening and one closing angle bracket `<p>` and the the name of the tag in between whereas a closing tag has a slash  `</p>` as well to indicate the closing part of the tag([list of tags at W3SCHOOLS](https://www.w3schools.com/TAGS/default.ASP)).

---
# ***All html pages***
```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Metadata goes here -->
  </head>
  <body>
    <!-- Content goes here -->
  </body>
</html>
```
---
1. `<!DOCTYPE html>` Tells the browser which version of html we are using
2. `<html>...</html>` the content of the page goes here.
3. `<head>...</head>` Here goes the content that gives more info to the browser about the page
4. `<body>...</body>` Here goes the content of the page.

---
# ***Commonly used tags***
- Title `<title>`
- Paragraph `<p>`
- Headings `<h1>` `<h6>`

---
- Lists
    - ordered `<ol>`
    - un-ordered `<ul>`
- Emphasis(Italic) `<em>`
- Strong(Bold) `<strong>`
- Comments `<!-- -->` cmd(ctrl) + /
---
# ***Empty(self-closing) tags***
- Line Break `<br/>`
- Horizontal rules `<hr/>`