### NOTES: SECTION { Introduction to Basic CSS} ###
FreeCodeCamp

**NOTES**:
example
<h2>
some attributes
</h2>

When applying a CSS style directly to an element it would look like this:
<h2 style= " style argument">argument </h2>
the style attribute was in the h2 element then the h2 element was closed at the end of the line
The style attribute is embedded in the h2 tag


Adding a style block
<style> some attribute </style>
allows an attribute to be applied to all items defined within the block

A defined class can be applied to any and multiple elements directly

<p> class="red-text"
<h1> class="blue-text"
<h2> class="green-text"

color is a CSS property.......color:blue;
fontsize is a CSS property ......font-size: xxpx;
font-family is a CSS property.... font-family:  font;

font fAMILY NAMES NEED TO BE WRAPPED IN QUOTES IF THERE IS A SPACE IN BETWEEN LIKE : OPEN SANS  SHOULD BE "OPEN SANS"

Comments are <!--  -->
Separating fonts with a comma gives a fallback font incase the first font is unavailable

width is a CSS property

##BORDERs##
CSS BORDERS:

in the syyle elements
you always specify classes with a .
and you always speficy id's with a #

Todays notes:

A pseudo-class is a keyword that can be added to selectors, in order to select a specific state of the element.
For example, the styling of an anchor tag can be changed for its hover state using the :hover pseudo-class selector

The CSS offsets of top or bottom, and left or right tell the browser how far to offset an item relative to where it would sit in the normal flow of the document. You're offsetting an element away from a given spot, which moves the element away from the referenced side (effectively, the opposite direction). As you saw in the last challenge, using the top offset moved the h2 downwards. Likewise, using a left offset moves an item to the right.

When elements are positioned to overlap (i.e. using position: absolute | relative | fixed | sticky), the element coming later in the HTML markup will, by default, appear on the top of the other elements. However, the z-index property can specify the order of how elements are stacked on top of one another.

On a website, color can draw attention to content, evoke emotions, or create visual harmony. Using different combinations of colors can really change the look of a website, and a lot of thought can go into picking a color palette that works with your content.


