# HTML - CSS - JAVASCRIPT

Ghi chú lại các trường hợp ít sử dụng nhưng hay xuất hiện trong quá trình làm việc của 1 developer.

## 1 - HTML

Difference Between Inline and Block Elements in HTML

| Block Elements                                                     | Inline Elements                                                                  |
| ------------------------------------------------------------------ | -------------------------------------------------------------------------------- |
| Block elements always start from a new line.                       | Inline elements never start from a new line.                                     |
| Block elements cover space from left to right as far as it can go. | Inline elements only cover the space as bounded by the tags in the HTML element. |
| Block elements have top and bottom margins.                        | Inline elements don't have a top and bottom margin.                              |
| Examples of block elements - \<p>,\<div>,\<hr>.                    | Examples of inline elements - \<span>,\<br>                                      |

- https://htmlreference.io/

## 2 - CSS

Setting the viewport help the browser instructions on how to control the page's dimensions and scaling. ([REF](https://www.w3schools.com/css/css_rwd_viewport.asp))

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

Media query is a CSS technique introduced in CSS3. It uses the @media rule to include a block of CSS properties only if a certain condition is true. ([REF](https://www.w3schools.com/css/css_rwd_mediaqueries.asp))

```css
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
  body {
    background-color: lightblue;
  }
} /* Small devices (portrait tablets and large phones,
600px and up) */
@media only screen and (min-width: 600px) {
  ...;
} /* Medium
devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  ...;
} /* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
  ...;
} /* Extra large devices (large laptops and
desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
  ...;
}
/* The web page will have a lightblue background if the orientation is in landscape mode: */
@media only screen and (orientation: landscape) {
  body {
    background-color: lightblue;
  }
}
```

- [Example CSS responsive](https://www.w3schools.com/css/tryit.asp?filename=tryresponsive_breakpoints)
- [CSS template](https://www.w3schools.com/css/css_rwd_templates.asp)

### Reference

1. https://www.w3schools.com

```html
<ul>
  <li>Home</li>
  <li>Data 1</li>
  <li>Data 2</li>
  <li>
    Liên hệ

    <ul>
      <li>LH - Data 1</li>
      <li>LH - Data 2</li>
    </ul>
  </li>
</ul>
```
