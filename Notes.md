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

The Complementary Colors challenge showed that opposite colors on the color wheel can make each other appear more vibrant when placed side-by-side. However, the strong visual contrast can be jarring if it's overused on a website, and can sometimes make text harder to read if it's placed on a complementary-colored background. In practice, one of the colors is usually dominant and the complement is used to bring visual attention to certain content on the page.


Hue is what people generally think of as 'color'. If you picture a spectrum of colors starting with red on the left, moving through green in the middle, and blue on right, the hue is where a color fits along this line. In hsl(), hue uses a color wheel concept instead of the spectrum, where the angle of the color on the circle is given as a value between 0 and 360.

Saturation is the amount of gray in a color. A fully saturated color has no gray in it, and a minimally saturated color is almost completely gray. This is given as a percentage with 100% being fully saturated.

Lightness is the amount of white or black in a color. A percentage is given ranging from 0% (black) to 100% (white), where 50% is the normal color.

One way to add texture and interest to a background and have it stand out more is to add a subtle pattern. The key is balance, as you don't want the background to stand out too much, and take away from the foreground. The background property supports the url() function in order to link to an image of the chosen texture or pattern. The link address is wrapped in quotes inside the parentheses.

These pseudo-elements :: are used to add something before or after a selected element. In the following example, a ::before pseudo-element is used to add a rectangle to an element with the class heart:

.heart::before {
  content: "";
  background-color: yellow;
  border-radius: 25%;
  position: absolute;
  height: 50px;
  width: 70px;
  top: -50px;
  left: 5px;
}
