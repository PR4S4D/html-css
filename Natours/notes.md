- Box-sizing

  `box-sizing: border-box;`

  if you're not familiar with box sizing border box, what this does is to change the box model so that the borders and the paddings are no longer added to the total width or the total height

- Letter spacing

`letter-spacing: 35px;`

- CSS to put an element in the center

```
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
```

- Basic animation using keyframes

```
@keyframes moveInLeft {
  0% {
    opacity: 0;
    transform: translateX(-100px);
  }

  100% {
    opacity: 1;
    transform: translate(0);
  }
}
```

Then specify animation-name and animation-duration

```
  animation-name: moveInLeft;
  animation-duration: 5s;

```
