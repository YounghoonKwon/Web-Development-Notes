#### inline elements

- a
- span
- img

#### block elements

- 100% of width by default
  - p
  - h1-h6
  - div
  - ol, ul, li
  - form

#### display

- block: having whole width of the screen (can specify width or height manually)
- inline: allows sit next to each other
- inline-block: block + inline
- none

#### position

- static: all html elements are static by default. It means go along with the html rules and keep to the default html flow.
- relative: to position the element we select relative to how it would've been positioned.(use with left right top bottom). This depeneds on the previous position. It doesn't affect any other components.
- absolute: position the element relative to its parent. setting the element out of the flow
- fixed: fixed in the screen. (think when implementing nav-bar)

#### centering elements

- text align
- margin

#### font

- cssfontstack.com
- fonts.google.com (embedded font)

#### icon and gifs

- flaticon.com
- giphy.com

#### font-size

- to make dynamic font size, use %
- 100% == 16px
- 1em == 16px

- font size has inheriting characteristic.
  - ex: body has 2em, and child has 5em. then child actually has 7em
- rem: root em, ignore all the parent settings for the font size.

#### width, height

- scaled down based on their parent

#### float, clear

- use when wrapping around of certain element, DO NOT ABUSE
- float: places an element on the left or right side of its container, allowing text and inline elements to wrap around it.
- clear: to specify that which side of floating elements are not allowed to float.

#### button

- css3buttongenerator.com
