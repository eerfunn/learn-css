# Chapter 5: Box Model

- Every element in html using box concept for styling (cmiiw)
- The default value for box defined by "box-sizing" at it was "box-sizing: content-box"
- Content box only calculate the main element size without margin, border, and other attribute size. Example: if you have "h1", and you set it like:

```
h1 {
box-sizing: content-box;
border: 10px double red;
font-size: 1.5rem;
padding: 1.5rem;
width: 400px;
}
```

it will have a total width of:

```
400 + (16 * 1.5) + 10 = 434px
```

And sometimes, it'll make your page overflowing horizontally

- That's why, you can use "box-sizing: border-box" to make element's margin, border, and attribute included to the calculation of total width
