# Docs for the HTML <canvas> Element & Chart.js

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.
They’re easier to look at and convey data quickly, but they’re not always easy to create.


At first sight a < canvas > looks like the < img > element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed,
the <canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties.
  When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high.
  The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas,
  it will appear distorted.

If your renderings seem distorted, try specifying your width and height attributes explicitly in the <canvas> attributes, and not using CSS. 
  
note.it is not good practice to embed a script inside HTML. 
