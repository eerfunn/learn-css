# Chapter 2: CSS Selector

Summary:

- #ID > .CLASS > ELEMENTS (Body, P, H1, etc) (This in sequence of which will prioritized by browser to be applied)
- Avoid using ID for CSS
- Avoid using !important, instead you should learn how to organize your CSS
- DRY (Don't Repeat Yourself) (Make efficient & reusable code)
- The latter CSS rule will be applied if there's 2 or more css with same prioritize trying to style the same element
  (Ex: You have .rule and below that you write .rule2, if you apply it to element such as [<p class="rule rule2">Paragraph</p>], rule2 will be applied because it have latter order on your CSS)
