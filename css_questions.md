#### CSS Questions:

* What is the difference between classes and IDs in CSS?
  - IDs are specific to a single instance of an element, classes are for multiple elements.
* What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
  - CSS resets removes all built-in browser styling (making h1 look the same as p).
  - CSS normalizing provides a consistent cross-browser style baseline.
* Describe Floats and how they work.
  - Floats are magic and can only work when powered by enough faith.
  - When used on an element, other elements will flow around it (around the right if float: left;, vice versa)
  - Need to be mindful of when to clear the float (in case you don't want certain following elements to flow around it)
  - Also floating an element can cause the parent element to ignore its floating child's height properties; can be fixed by giving parent/containing element additional css (clearfix stuff)
* Describe z-index and how stacking context is formed.
  - Z-index enables control of layering elements. (Z for Z axis, see right hand rule)
  - Particularly useful if elements to be stacked are positioned absolutely or relatively such that stacking is inevitable.
* Describe BFC(Block Formatting Context) and how it works.
* What are the various clearing techniques and which is appropriate for what context?
* Explain CSS sprites, and how you would implement them on a page or site.
* What are your favourite image replacement techniques and which do you use when?
* How would you approach fixing browser-specific styling issues?
* How do you serve your pages for feature-constrained browsers?
  * What techniques/processes do you use?
* What are the different ways to visually hide content (and make it available only for screen readers)?
* Have you ever used a grid system, and if so, what do you prefer?
* Have you used or implemented media queries or mobile specific layouts/CSS?
* Are you familiar with styling SVG?
  - I've done it once to the extent of giving it a fill color and scaling it. And giving it a rotation animation.
* How do you optimize your webpages for print?
* What are some of the "gotchas" for writing efficient CSS?
* What are the advantages/disadvantages of using CSS preprocessors?
  * Describe what you like and dislike about the CSS preprocessors you have used.
* How would you implement a web design comp that uses non-standard fonts?
* Explain how a browser determines what elements match a CSS selector.
* Describe pseudo-elements and discuss what they are used for.
* Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
* What does ```* { box-sizing: border-box; }``` do? What are its advantages?
* List as many values for the display property that you can remember.
* What's the difference between inline and inline-block?
  - Inline elements
    - respect side margins and padding but not top or bottom.
    - cannot have a width or height set.
    - allow other elements to sit to their left and right.
  - Inline-block
    - allow other elements to sit to their left and right.
    - respect top and bottom margins and padding.
    - respect height and width.
* What's the difference between a relative, fixed, absolute and statically positioned element?
  - Relative means positioned relative to where the element itself would have been without additional position attributes
  - Absolute means positioned relative to its parent element, and coordinate-wise zeroes out the element.
  - Static is default for every single page element and is mainly used to forcefully remove some other type of positioning.
  - Fixed means relative to the browser window, not any of the elements.
* The 'C' in CSS stands for Cascading.  How is priority determined in assigning styles (a few examples)?  How can you use this system to your advantage?
  - from smallest priority to greatest: element tag name, class, ID, !important, HTML styling.
* What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
* Have you played around with the new CSS Flexbox or Grid specs?
* How is responsive design different from adaptive design?
* Have you ever worked with retina graphics? If so, when and what techniques did you use?
* Is there any reason you'd want to use `translate()` instead of *absolute positioning*, or vice-versa? And why?
