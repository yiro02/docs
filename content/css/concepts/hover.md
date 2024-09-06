---
 Title: 'Hover and Cursor'
 Description: 'hover CSS is a pseudo-class matches when the user interacts with an element with a pointing device, but does not necessarily activate it. It is generally triggered when the user hovers over an element with the cursor (mouse pointer).'

 Subjects:
  - 'Web Development'
  - 'Web Design'
  
 tags:
  -  'Definitions'
  -  'concepts'
  -  'suedo-class

 CatalogContent:
  - 'learn-css'
  - 'paths/front-end-engineer-career-path'
---
**hover CSS is a pseudo-class** matches when the user interacts with an element with a pointing device, but does not necessarily activate it. It is generally triggered when the user hovers over an element with the cursor (mouse pointer).' 

## background
 Styles defined by the :hover pseudo-class will be overridden by any subsequent link-related pseudo-class (:link, :visited, or :active) that has at least equal specificity. To style links appropriately, put the :hover rule after the :link and :visited rules but before the :active one, as defined by the LVHA-order: :link — :visited — :hover — :active.

 The :hover pseudo-class is problematic on touchscreens. Depending on the browser, the :hover pseudo-class might never match, match only for a moment after touching an element, or continue to match even after the user has stopped touching and until the user touches another element. Web developers should make sure that content is accessible on devices with limited or `non-existent hovering capabilities.`

## Example 1
```css
a {
  background-color: powderblue;
  transition: background-color 0.5s;
}

a:hover {
  background-color: gold;
}
```
 ## Video Walkthrough
 **Watch this video**  for a /*step-by-step/* demonstration on how to use hover in CCS <iframe width="300px" height = "300" src="https://youtu.be/tsqkmRng1r4?si=_1Bm571dx1aJ5Xwl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen> </iframe>
