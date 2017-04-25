# Down the SVG Rabbit Hole
 **with Robin Larsen**
R@robynlarsen.ca

 
SVG graphics is not photoshop not gif, its code. - Robin Larsen, Former Nuclear Engineer turned Front End Dev aka "Major Nerd."
**SVG for designers**

  Project goals and where we can take it:
  Are your goal stagnant or animated?
  Communicate clearly because the code from designers differ. When working with dev team you have to tell dev team what sketch most of her design team uses. 
  Exported code is sometimes shitty.
  Designers must run their code in their cmd runner and compress it a little bit. Assets including Adobe Illustrator and Sketch.

**How to export** 

  Export SVGs in Sketch
  View box –
  By default, exported SVG code in Sketch is really messy.
  1) Add SVGs to their own artboards prior to exporting
  2) Select svg layers – you can't use dotted arrow select, will need to select in the layers panel
  3) Flatten - removes the inline transform/translate/rotate attributes
   

**SKETCH WORKFLOW**

  1.       Name your layers - it translates to an id
  2.       add SVGs to their own artboard
  3.       Use icon- & logo- prefix for svg icons
  4.       Try to add all simple icons to one svg file
  Utilize <use> element (discussed later)
  5.       Reduce layer nesting to prevent complex inline SVG nesting
  6.       Flatten and merge layers
  7.       Reduce the complexity of shapes and reduce points - will reduce <path> elements

 
**SVG optimization** 

  To optimize or not to optimize? Go back to your project goals. 
  If you're making a lot of animation then you want to take care of the code CSS, SVG, I got, viframe video (Max-width :100%) so it doesn't go outside the browser.

**Fed SVG workflow** 

  ·  Name your layers - it translates to an inline id
  ·  Use icon- & logo- prefix for svg icons & logos, respectively
  ·  Remove inline width and height attributes
  ·  Try to add all simple icons to one svg file
  ·         Utilize <use> element
  ·  svgo --pretty icons/
  ·  Other svgo parameters include --addClassesTOSVGElement -s=svgClassRemove inline width or height

Because it's a vector image and it's not going to become pixelated and we already applied the max width 100%
So it's already going to apply max width m
 
SVGo--pretty icons ;
 
Advanced SVG 
Filters : lighting effects and Gaussian blur 
Imagine in ps 
Imagine in code you can do in one line no exporting in PNG OR JPG
 
Filters 

https://d2mxuefqeaa7sj.cloudfront.net/s_481EAE729CAF5152D3E9B65A5B91E315E3B5E9A51861AA8EED6F161BA89CC6FA_1493100848810_filtersSVG.PNG

https://d2mxuefqeaa7sj.cloudfront.net/s_481EAE729CAF5152D3E9B65A5B91E315E3B5E9A51861AA8EED6F161BA89CC6FA_1493100926528_fillcolor.PNG

https://d2mxuefqeaa7sj.cloudfront.net/s_481EAE729CAF5152D3E9B65A5B91E315E3B5E9A51861AA8EED6F161BA89CC6FA_1493100971181_filterOther.PNG


 
When working on project you should use: 
**Ruby helper**

  This is a method of putting the code in a separate svg file that you can link back to your page without having a bulky code. 
https://d2mxuefqeaa7sj.cloudfront.net/s_481EAE729CAF5152D3E9B65A5B91E315E3B5E9A51861AA8EED6F161BA89CC6FA_1493100799954_ruby_helper.PNG


 
SVG 2.0  shipper September 2015 
 
Slides [robynlarsen.ca/speaking/level-up-svg](http://robynlarsen.ca/speaking/level-up-svg)

