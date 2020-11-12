# Responsive Overview

Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop. Responsive web design is focused around providing an intuitive and gratifying experience for everyone. Desktop computer and cell phone users alike all benefit from responsive websites.

## Initializing Media Queries
There are a couple different ways to use media queries, using the @media rule inside of an existing style sheet, importing a new style sheet using the @import rule, or by linking to a separate style sheet from within the HTML document.

### Logical Operators in Media Queries
Logical operators in media queries help build powerful expressions. There are three different logical operators available for use within media queries, including and, not, and only.

## Mobile First
One popular technique with using media queries is called mobile first. The mobile first approach includes using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows.

## CSS Viewport Rule
Since the viewport meta tag revolves so heavily around setting the styles of how a website should be rendered it has been recommend to move the viewport from a meta tag with HTML to an @ rule within CSS. This helps keep the style separated from content, providing a more semantic approach.

## Flexible Media
The final, equally important aspect to responsive web design involves flexible media. As viewports begin to change size media doesn’t always follow suit. Images, videos, and other media types need to be scalable, changing their size as the size of the viewport changes.

One quick way to make media scalable is by using the max-width property with a value of 100%. Doing so ensures that as the viewport gets smaller any media will scale down according to its containers width.

----------------------------------------------------------------

## What is “Float”?
Float is a CSS positioning property. To understand its purpose and origin, we can look to print design. In a print layout, images may be set into the page such that text wraps around them as needed.
floats can be used **to create entire web layouts.**
Float’s sister property is ***clear***. An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float. Again an illustration probably does more good than words do.
One of the most frequent uses of the clear property is “clear:both”.This allows you to reset the flow of elements, as opposed to continuing to maintain a right, left and normal flow. 
### Problems with Floats
1-Pushdown
2-Double margin bug
3-3px Jog
4-Bottom margin bug

The float property also gives an indication of an element’s relationship to surrounding elements.


-----------------------------------------------------------------
## SMACSS

What is it?
SMACSS (pronounced “smacks”) is more style guide than rigid framework. There is no library within here for you to download or install. There is no git repository for you to clone. SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process. It is an attempt to document a consistent approach to site development when using CSS. 



