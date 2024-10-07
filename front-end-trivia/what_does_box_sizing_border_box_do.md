---
noteId: 1728321801878
---

What does `* { box-sizing: border-box; }` do?

---

`* { box-sizing: border-box; }` applies `border-box` sizing to all elements.

Default `box-sizing: content-box` only considers content size for `height` and `width`.

`border-box` includes `padding` and `border` in calculations:

- `height` = content height + vertical padding + vertical border
- `width` = content width + horizontal padding + horizontal border
