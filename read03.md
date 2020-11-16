# Javascript Templating :
Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.

mustache.js is an implementation of the mustache template system in JavaScript. It is often considered the base for JavaScript templating. And, since mustache supports various languages, we don’t need a separate templating system on the server side.

---------------------------------------------------------
# A guide for flexbox :

-Display
This defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.

Note that CSS columns have no effect on a flex container.

### Properties for parent:
-Flex-direction
1-row (default): left to right in ltr; right to left in rtl
2-row-reverse: right to left in ltr; left to right in rtl
3-column: same as row but top to bottom
4-column-reverse: same as row-reverse but bottom to top

-Flex-wrap
1-row (default): left to right in ltr; right to left in rtl
2-row-reverse: right to left in ltr; left to right in rtl
3-column: same as row but top to bottom
4-column-reverse: same as row-reverse but bottom to top

-flex-flow
This is a shorthand for the flex-direction and flex-wrap properties, which together define the flex container’s main and cross axes. The default value is row nowrap.

-Justify content
This defines the alignment along the main axis. It helps distribute extra free space leftover when either all the flex items on a line are inflexible

-Align item
This defines the default behavior for how flex items are laid out along the cross axis on the current line

-Align content
This aligns a flex container’s lines within when there is extra space in the cross-axis

### Properties for children

-Order
the order property controls the order in which they appear in the flex container

-Flex-grow
This defines the ability for a flex item to grow if necessary.

-Flex-shrink
This defines the ability for a flex item to grow if necessary.

-Flex-basis
This defines the default size of an element before the remaining space is distributed.

-Align-self
This allows the default alignment (or the one specified by align-items) to be overridden for individual flex items.

