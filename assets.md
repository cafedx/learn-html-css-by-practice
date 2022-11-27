# Assets

## Typography system

Using [TypeScale](https://type-scale.com/?size=10&scale=1.250&text=A%20Visual%20Type%20Scale&font=Inter&fontweight=400&bodyfont=body_font_default&bodyfontweight=400&lineheight=1.75&backgroundcolor=%23ffffff&fontcolor=%23000000&preview=false), we are able to develop a persistent font-size across whole projects.

- Base `font-size: 62.5%` - 10px
- Scale `1.250 Major Third`
- Font Family `Inter`
- Font Weight: `400`

<img src="assets/major third 1.250 base 10px inter w400.jpg" alt="type scale major third 1.250 base 10px inter w400" width="600px">

**Font sizes (px)** - _we use rem_

`10 / 12 / 16 / 20 / 24 / 30 / 38 / 48 / 60`

**Font weights**

Default: `400`
Medium: `500`
Semi-bold: `600`
Bold: `700`

**Line heights**

Default: `1`
Small: `1.05`
Medium: `1.2`
Large: `1.8`
Paragraph default: `1.6`
Headings : `0.9 - 1.1`

**Letter spacing**

Headings: `-0.5px`
SubHeadings, Paragraphs: `0.75px`

**Spacing system (px)** - _we use rem_

2 / 4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 80 / 96 / 128

<details>
<summary><strong>CSS Code</strong></summary>

```css
/*
**Font sizes (px) - we use rem**

`10 / 12 / 16 / 20 / 24 / 30 / 38 / 48 / 60`

**Font weights**

Default: `400`
Medium: `500`
Semi-bold: `600`
Bold: `700`

**Line heights**

Default: `1`
Small: `1.05`
Medium: `1.2`
Large: `1.8`
Paragraph default: `1.6`
Headings : `0.9 - 1.1`

**Letter spacing**

Headings: `-0.5px`
SubHeadings, Paragraphs: `0.75px`

**Spacing system (px) - we use rem/em**

2 / 4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 80 / 96 / 128

*/

@import url("https://fonts.googleapis.com/css?family=Inter:400,500,600,700");

html {
  font-size: 62.5%; /* 10px */
}

body {
  /* 
  All child elements will inherit these typographies but some elements like button
   */
  font-family: "Inter", sans-serif;
  font-weight: 400;
  font-size: 1.6rem;
  line-height: 1; /*Reset line-height*/
  letter-spacing: 0.75px;
}

h1,
h2,
h3,
h4,
h5 {
  font-weight: 500;
  letter-spacing: -0.5px;
  line-height: 0.9; /* 0.9- 1.1*/
}

h1 {
  font-size: 4.8rem;
}

h2 {
  font-size: 3.8rem;
}

h3 {
  font-size: 3rem;
}

h4 {
  font-size: 2.4rem;
}

h5 {
  font-size: 2rem;
}

small,
.text_small {
  font-size: 1rem;
}

button,
input,
optgroup,
select,
textarea {
  /*  These have user agent styles, so we should manually set inherit*/
  font-family: inherit;
  font-size: inherit;
  font-weight: inherit;
  line-height: inherit;
  letter-spacing: inherit;
}
p {
  line-height: 1.6;
}
```

</details>

---

## Free Human Avatars:

- [UIFaces](https://www.uifaces.co/browse-avatars)

---

## Free Icons:

- [Hero Icons](ttps://heroicons.com)

---

## Free Pictures:

- [FreePik](https://www.freepik.com/search?format=search&last_filter=selection&last_value=1&selection=1)

- [Unsplash](https://unsplash.com/s/photos/frontend)

---

## Colors:

- [Coolors contrast checker](https://coolors.co/contrast-checker/fff-000)
- [OpenColor palette](https://yeun.github.io/open-color)

---

## Idea

- [ScreenLane](https://screenlane.com)
- [AWWWards](https://www.awwwards.com/websites)
- [Land-Book](https://land-book.com)
- [OnePageLove](https://onepagelove.com)
