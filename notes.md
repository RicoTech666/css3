## Text-shadow

Each shadow is specified as two or three `<length>` values, followed optionally by a `<color>` value. The first two `<length>` values are the `<offset-x>` and `<offset-y>` values. The third, optional, `<length>` value is the `<blur-radius>`. The`<color>` value is the shadow's color.

When more than one shadow is given, shadows are applied front-to-back, with the first-specified shadow on top.

eg.
```
 .box {
   text-shadow: 1px 1px 2px red, 0 0 1em blue, 0 0 0.2em blue;
 }
```

## Pseudo-class

The `:disabled` CSS pseudo-class represents any disabled element. An element is disabled if it can't be activated (selected, clicked on, typed into, etc.) or accept focus. The element also has an enabled state, in which it can be activated or accept focus.

## Gradient
If one wants to add a progressive transition between two or more colors for background, gradients function should be used.
```
 linear-gradient(), radial-gradient(), repeating-linear-gradient(), repeating-radial-gradient(), conic-gradient()
```
For example, if one wants to add a background with a few color transition diagonally from top left to bottom right, the css code should be as follow:
```
 background: linear-gradient(to top left, #ee7752, #e73c7e, #23a6d5, #23d5ab);
```

