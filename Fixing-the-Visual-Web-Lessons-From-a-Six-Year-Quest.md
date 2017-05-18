# Fixing the Visual Web: Lessons From a Six Year Quest
Chris Zacharias


## **Visual media on the Web**

**How visual media on the web has always worked**
**Subject** → Camera → Image → Storage ←Network ←Application ←Interface ←Display ←**Viewer**

**2007: Mobile devices introduced**

- One image can be displayed on different types of screens
  - Can no longer predict where/why/how visual media will be displayed
  - Heavier penalties if you approximate incorrectly
  - Time consuming to optimize one image for multiple viewports
- To keep up, visual media has to become dynamic
  - Adapt to network, device etc.
- Output needs to be driven by signals from the environment

**Subject** → Camera → Image → Storage → *[NEED NEW LAYER HERE]* ←Network ←Application ←Interface ←Display ←**Viewer**


## **Idea: build a computer graphics card for the Internet**

**Why is one needed now?**

- Distance from visual media to brain is decreasing (becoming more personal)
  - Movie screen → Television → Computer → VR
- The Web is primary conduit of visual media
  - Over 80% of the average web page is visual media (images, video, fonts, styles)
- The Web wasn’t designed to do this
  - <img> tag was almost scrapped from the first HTML spec - concern that images would cause the Internet to be used for porn
  - Other media types unaccounted for until approximately 2010
    - First YouTube HTML5 <video> player
- Requires a “layer cake” of technology and shims
  - E.g., How 3D currently works in the browser — not natively handled:
    HTML Document → JS Loader → Canvas Element → JS Logic → WebGL content → glShader
- Web technologies still take cues from print media (margin, padding, stylesheets)
- The Web needs to advance as a graphics platform

**How do we get there?**

- Start with the infrastructure
  - Then adapt browsers, software, and services
- Explore new metaphors
  - Window = scene
  - DOM = scene graph
  - Document = stage
  - Elements = actors
  - Styles = properties
  - Scripts = scripts and behaviours
- Keep best parts of the web
  - View Source - means anyone can learn
  - Browser is the development environment
  - Preserve indexing and searchability
  - HTTP resource loading


