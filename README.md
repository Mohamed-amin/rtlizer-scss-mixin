# rtlizer-scss-mixin
A small SCSS mixin to change RTL related values
I was using it in a current project and I thought its can be resuable, 
enjoy :), and if you can suggest a less sillier name for it please do! :)
# How to use it
```js
@include rtlizer('text-align')
```
Or if there is a value
```js
@include rtlizer('letter-spacing', '1px')
```

Till now it supports: Letter-sapacing, text-align, float, position (for left or right), or any property with direction in it i.e. marign-left/right, border-left. 
