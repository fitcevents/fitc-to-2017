# So I Decided to Program a Solar System Simulator
or how a Javascript experiment became a t-shirt
by [**Martin Vézina**](http://fitc.ca/speaker/martin-vezina/?event=21332)


## Part 1. jsOrrery: a personal javascript project
- visited Kennedy Space Centre and found a renewed interest in his childhood love of space
- inspired after seeing images of trajectories of Apollo craft
- decided that instead of wasting time on Reddit, he’d waste time coding a javascript pet project
- idea was to model an orrery in the browser
- looked up an old Flash project he’d done that used some of the basic math that this project needed
- using three.js to computer positions of planets 
- created a 2D simulation on Canvas
- later added the 3rd dimension to it, using 3d context in Canvas
- added a “shitload of stars - because why not” - found a data set with the positions of all kinds of stars and placed them in a particle system in a sphere that is attached to the camera position
- positioning the moon is particularly troublesome - in the 60’s two French astronomers developed a massive formula for calculating the moon’s position - it accounts for all the different factors that effect the moon’s position. Using this formula was able to get things precise enough to simulate an eclipse.
- once the moon was in place decided to simulate an Apollo mission
- let it sit on Github for awhile, then posted to Google Experiments, after which it got featured on NASA’s website


## Part 2: spacetime coordinates

A kickstarter project to produce a t-shirt

- artist’s initial plan was to taker a date provided by a backer and give them a t-shirt with the solar systems positions on that date
- ended up raising $83000 (Euros)
- could not fulfill the demand by hand
- took some artistic liberties to blow out the inner orbits to make them visible
- contacted Martin to see if he could help
- had to figure out some changes to handle the artistic vision
- to draw the orbits, thought maybe he’d used SVG, but landed on using Illustrator scripting to generate the final output files directly
- the 3D version was created using vertices on the path of the orbits, then drawing lines between them
- used these vertices to calculate how to draw the ellipses representing the orbits
- ended up being able to provide her with Excel files that she could use to generate the designs for printing

“Don’t be afraid of not knowing - there’s a beauty to imperfection”
“The destination is not what counts - it’s the unexpected that makes the trip memorable”
“Fun stuff can be serious - your pet projects might be more valuable than you think”


