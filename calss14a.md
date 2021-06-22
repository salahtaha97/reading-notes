#  CSS Transforms, Transitions, and Animations
## Transforms
With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

example:
- div {
  - -webkit-transform: scale(1.5);
   -   -moz-transform: scale(1.5);
    -    -o-transform: scale(1.5);
  -     transform: scale(1.5);
- }
## Transitions
a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

example:
- .box {
-    background: #2db34a;
-    border-radius: 6px
-    transition-property: background, border-radius;
-    transition-duration: 1s;
-    transition-timing-function: linear;
-  }
-  .box:hover {
-    background: #ff7b29;
-    border-radius: 50%;
-  }

## Animations
Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.

example :
- @keyframes slide {
 - 0% {
 -   left: 0;
 -   top: 0;
 * }
 - 50% {
 -   left: 244px;
 -   top: 100px;
 - }
 - 100% {
 -   left: 488px;
-     top: 0;
-  }
- }

