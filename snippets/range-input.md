---
title: ange Input
tags: Interactivity, Beginner
---

# Displays an input:range with styles and hover/active/focus animations.

```html
<input class="range-input" type="range"/>
```

```css
.range-input {
  height: 1em;
  background-color: #bbb9ae;
  -webkit-appearance: none;
  width: 85%;
  border-radius: 0.3em;
  box-shadow: 0 0 3px 1px #777;
  transition: all 0.2s;
}
.range-input:focus {
  outline: none;
  box-shadow: 0 0 5px 1px #666;
  height: 1.25em;
  border-radius: 0.5em;
}
.range-input::-webkit-slider-runnable-track {
  width: 100%;
}
.range-input::-webkit-slider-thumb {
  -webkit-appearance: none;
  width: 1.1em;
  height: 2.4em;
  background-color: #ccc;
  border-radius: 0.55em;
  box-shadow: 0 0 5px #444;
  transition: all 0.1s;
}
.range-input::-webkit-slider-thumb:hover {
  background: #e6e6e6;
  width: 1.4em;
  height: 2.3em;
  border-radius: 1.2em;
}
.range-input::-webkit-slider-thumb:active {
  box-shadow: 0 0 3px 2px #444;
}
```

#### Explanation

- Use a `input:range` element with the class `range-input`.
- Note that you can modify the `width` and `height` properties of the track.
- Also you can change the bar color with the `background-color` property in `range-input`.
- By last change the pointer style using the `::-webkit-slider-thumb` selector in `range-input`.
- Change `transition` in each selector if you want the animation to be faster or slower.


#### Browser support

- https://caniuse.com/#feat=css-transitions
- https://caniuse.com/#feat=input-range