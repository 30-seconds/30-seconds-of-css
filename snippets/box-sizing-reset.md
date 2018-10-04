### Box-sizing reset

Resets the box-model so that `width`s and `height`s are not affected by their `border`s or `padding`.

#### CSS

```css
html {
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: inherit;
}
```

#### Demo

#### Explanation

1. `box-sizing: border-box` makes the addition of `padding` or `border`s not affect an element's `width` or `height`.
2. `box-sizing: inherit` makes an element respect its parent's `box-sizing` rule.

#### Browser support

<span class="snippet__support-note">✅ No caveats.</span>

* https://caniuse.com/#feat=css3-boxsizing

<!-- tags: layout -->
