# Interactive Light
@jaredrawk
@argodesigned

Looking at his body of work, it’s been observed that he has an obsession with turning on and off lights.

Sources of light:

- fire
- RGB LED’s
- infrared light: led’s or depth sensors
- projectors - especially ultra-short throw projectors (can cover a huge table when placed only 12” above it)

Science of light, important, but for a later conversation 😃 

Consider these things about light:

- aesthetics
  - the colour of the light combines with the surfaces it hits, giving it a differing appearance, a familiar one, as opposed to the bright lights glaring out of devices
- information
  - carries lots of feedback about the object for the viewer
- magic
  - the visible part of light is what’s of interest to him
  - infrared is magical in that you can’t see it

Social lamps

- focused infrared light can approximate the human gaze, about a 20 degree field 
- TSOP 38, a diode that can screen out infrared light unless it’s interleaved at 38hz (can get differing frequency diodes)
- SparkFun Red Stick - Arduino Uno on tiny little USB board, plugged into iPad power adapter for power, plug the adapter into Edison adapter, screw it into a lamp and you have a portable lighting computer.
- goal of project was to turn off lamps based on how many people are gazing at them
- use Adafruit NeoPixels and Uber Guide (don’t cheap out on LED’s, often they don’t work well and will fail, probably need to spend $0.50 per pixel to get good quality)
- often when developers switch to hardware, they area mystified by the hardware and how it works, takes a long time to learn debugging hardware
- used a little infrared emitting badge to send out pulses read by TSOP

RGB Wall

- original sketch for the concept, actually had no RGB wall, did feature the social lamps though
- led to working with LED tealights with RGB controls by remote
- started figuring out how to wire all the tealights together rather than using the batteries
- got little custom dowels from Vancouver company called Bare Woods to stick into the battery compartments
- “I had no idea what I was doing at the start. I just wanted to build a giant lightbrite, one Google search at a time.”

Mixed Reality

- did some concept videos
- started building prototypes, ie. Pong on a table taop
- learned about the kinds of interfaces needed for these mixed reality experiences
  - fitment - making sure you have flat, clear spaces to project onto - using Kinect to find those spaces in the environment
  - participation - the interface invites the user to interact with the environment
  - augmentation - what is it that you actually put on the surface? often ended up using white light to project UI, data and feedback
  - coordination - identifying what is on the surface, the kinds of objects so that you can respond accordingly - lots of calibration, machine learning, etc


