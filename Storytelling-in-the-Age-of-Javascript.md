# Storytelling in the Age of Javascript

## Sarah Drasner

http://twitter.com/sarah_edo
http://slides.com/sdrasner/storytelling-js

**Alignment and Communication**

- everyone on the project has different views and objectives (get a 1000 clicks, make it match the brand aesthetic, make it load faster, etc)
- without a balance that includes compelling and captivating content and UI, it doesn’t matter how fast your site is

Start at the end: know the goal and work backwards, this helps to validate that you’ve been successful, if the users are getting to the end, you’ve succeeded.

As designers and developers our job is to remember that our users don’t know anything about our site, especially compared to us. “Things need to be as easy as possible for users to explore.”

**Create Clarity!**

**Features:**

- write them all down on a post note
- classify them into:
  - customers love
  - stuff that makes us money
  - stuff that makes us stand out against competitors
  - everything else
- get rid of the “everything else” stuff, it’s taking up space that could be used for the other stuff

**Personality**
Clippy - represents the bad, annoying person, keeps popping up asking the same things

- he was annoying because his personality was annoying
- in a test, Clippy’s personality was adjusted, made him more sarcastic, and people suddenly started liking him more

**Good examples:**

- onboarding at Codepen, conversational, but very easy to leave at any time
- Smashing Mags cat mascot, creates strong brand association

**Netflix is good and bad:**

- cites user hack to make two accounts, one for normal and one for when you are drunk as ways to hack Netflix’s machine learning recommendations
- suggests http://playground.tensorflow.com as place to play with machine learning

**Loaders**:

- reducing impact of perceived wait times
- a good loader can reduce the perceived load time by 60%
- uncertain waits are longer than know waits
- Disney and airports understand that the entertainment while waiting is valuable
- start user on a journey to make them feel like there is progress, ie. this is why doctor’s move you into a waiting room before they come in, makes you feel like you have become the process
- Codepen has a massive loader collection
- SVG’s are great for loaders, fast, flexible, responsive, animating, can be super small in file size
- provide feedback about what’s happening while loading

Foreshading and hints, can be really useful for prepping the user for where they are going. Animated SVG sequence can preview for the user what is about to happen once the site/app loads. Do some quick UI hints, very visual, fast and can improve the experience for the user once they are able to interact.

**Timing**

- the display of elements prematurely can be really disruptive
- animations that are too slow or too fast can ruin the effect, whether it’s meant to funny or surprising, etc.
- SVG filter trick - wait and don’t apply them until the exact moment you need them, then immediately remove them when the sequence is done that needed them
- don’t take too long to get a sequence complete either

**Transitions**

- think about how to created smooth transitions between visual states
- rather than have components on screen that animate independently, consider making them relate, ie. rollover one component, but don’t trigger rollover on another until the off transition has finished on the first one
- makes the experience smoother and connected

**On Feature Requirements**
Write out:
[as a user][I expect that][so that I can…]

**Consistency**
Many people think Material Design is about motion design, however the challenge is that Material Design looks like Google, thereby diminishing your own branding.

Have an opinion on motion design, be consistent.

**User Interaction Driven**

- make the user part of the story, have them share a part of themselves to show how they are connected to the story
- interactions with data visualizations
- Scrollytelling - revealing the story on the scroll
  - an interactive visualization of every line in Hamilton

Sarah’s book: SVG Animations published by O’Reilly
http://shop.oreilly.com/product/0636920045335.do

