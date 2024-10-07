---
noteId: 1728321801878
---

What does `* { box-sizing: border-box; }` do?

---

`* { box-sizing: border-box; }` makes every element on the page use the box-sizing: border-box approach for calculating the elements height and width.

By default, elements have `box-sizing: content-box` applied, and only the content size is being accounted for if an element has `height` and `width` specified. `box-sizing: border-box` changes how the `width` and `height` of elements are being calculated, `border` and `padding` are also being included in the calculation. The `height` of an element is now calculated by the content's `height` + vertical `padding` + vertical `border` width. The `width` of an element is now calculated by the content's `width` + horizontal `padding` + horizontal `border` width.
