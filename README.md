# 更现代的 CSS Rest

原文：[https://piccalil.li/blog/a-more-modern-css-reset](https://piccalil.li/blog/a-more-modern-css-reset)

```css
*,
:after,
:before {
  box-sizing: border-box;
}
html {
  -moz-text-size-adjust: none;
  -webkit-text-size-adjust: none;
  text-size-adjust: none;
}
blockquote,
body,
dd,
dl,
figure,
h1,
h2,
h3,
h4,
p {
  margin-block-end: 0;
}
ol[role='list'],
ul[role='list'] {
  list-style: none;
}
body {
  line-height: 1.5;
  min-height: 100vh;
}
button,
h1,
h2,
h3,
h4,
input,
label {
  line-height: 1.1;
}
h1,
h2,
h3,
h4 {
  text-wrap: balance;
}
a:not([class]) {
  color: currentColor;
  text-decoration-skip-ink: auto;
}
img,
picture {
  display: block;
  max-width: 100%;
}
button,
input,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
}
textarea:not([rows]) {
  min-height: 10em;
}
:target {
  scroll-margin-block: 5ex;
}
```
