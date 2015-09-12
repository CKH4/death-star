# Stylus Death Star Mixin
A stylus mixin that makes a single element death star. You can still add your own styles afterwards but changing some things might make it display incorrectly.

It comes in two types, normal and strict:
- Normal lets you apply any styles to it, even if makes it display incorrectly
- Strict overrides your styles in favor of the ones in the mixin

### How to use:

- in your html add a death star element (the class name doesn't matter)
```HTML
<div class="death-star"></div>
```

- in your stylus file include the mixin
  - either by using @include
  - or by copying and pasting the mixin

- to call the mixin
```stylus
.death-star
  death-star(100px)
```
