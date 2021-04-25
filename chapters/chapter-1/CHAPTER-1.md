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
### ***CHAPTER 1***
##### _Tools and setup_

---
# ***1. Introduction***
Learning _`HTML`_, _`CSS`_ and _`JavaScript`_ is hard, but it doesn’t have to be. We will walk through everything from setting up [VSCode](https://code.visualstudio.com/)(our text editor) to building full-fledged web apps.

![becoming a web dev](./assets/becoming-a-web-developer.png)

---
# ***2. HTML CSS and JAVASCRIPT***
HyperText Markup Language (HTML), Cascading Style Sheets (CSS), and JavaScript are the languages that run the web. They’re very closely related, but they’re also designed for very specific tasks.
___
- HTML is for adding meaning to raw content by marking it up.
- CSS is for formatting that marked up content.
- JavaScript is for making that content and formatting interactive.

---
![html css and js](./assets/html-css-javascript.png)

---
```html
<!-- html -->
<p id='some-paragraph'>This is a paragraph.</p>
```
```css
/** css **/
p {
  font-size: 20px;
  color: blue;
}
```
```js
/** JavaScript **/
const p = document.getElementById('some-paragraph');
p.addEventListener('click', function(event) {
  p.innerHTML = 'You clicked it!';
});

```

---
# ***3. Web development***
Mastering these 3 tools(skills) will help you ground yourself into web development, aside learning how to deploy a website you'll learn some frameworks and libraries that can help you work faster.

---
![languages vs web dev](./assets/languages-vs-web-dev.png)

---
# ***4. Web publishing***
So, what is it to “learn” HTML and CSS? We like to look at it through a historical lens into the printing industry. Back in the days of the original printing press, printers created documents by arranging metal characters, dipping them in ink, and pressing them onto a piece of paper.

---
In a lot of ways, that’s exactly what web developers do, except instead of arranging moveable type, they write HTML and CSS. We’re concerned with the same task as they were: conveying content in meaningful ways. We even deal with the same presentational issues they did, like selecting the font to use, setting the size of headings, and determining the space between lines of text.

---
![bg fit](./assets/web-publishing.png)