---
noteId: 1728323456597
---

How is the width of a non-floated block element determined if no width is specified?

---

If no `width` is specified, a non-floated block element will typically expand to fit the width of its containing block (which is often, but not always, the parent element) minus `padding`, `border`, and `margin`. This behavior can be altered by setting a `width`, `max-width`, or applying other constraints.
