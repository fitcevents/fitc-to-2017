# Designing for Voice
with Mitch Seguin

**Why Does it feel like COnversational UI is exploding?**

- API proliferation
- The hardware is here and cheat (far-field voice input processing)
- The science is ready for prime time. It’s accessible to people without PhDs (in math, cognitive science)
  - Natural language understanding
  - Automatic speech recognition
  - Text to speech
- Machine Learning is making conversation easier

**Voice Platforms**

- Virtual assistants (e.g. Siri, Google Now, Cortana)
- Amazon Alexa 
- Google Home
- Chatbots

PRO TIP: Embed yourself into the technology if you plan to work on it.

**Basic MEchanics and Architecture**

- A dumb device (e.g. Echo) listens to your voice, then Alexa interprets it utterance to intent)
- Syntax
  - Skill
    - When writing an app, or “skill” for the Amazon Echo, you have to provide examples of how your users might phrase their requests
  - Intent
    - Your app for the Amazon Echo is going to have one or more capbilities or features. In the nomenclature of the Amazon Skills Kit
  - Utterance
    - A spoken phrase that activates an Intent is called an Utterance, and there may be many valid Utterances that yo will want to accept for each of your app’s Intents
  - Ask and Tell
    - Invoking a skill with spefici intent
    - Invocation name and request provided in a supported phrase with ‘ask’, ‘tell’ and other phrases

**Designing for Voice is Hard**

- No UI
  - You need to be very precise about the use case and how you expect your users to interact with it so they can do it naturally
- People are unpredictable
  - Have to do a lot of upfront thinking about how people might really use this thing
  - Usability testing is important! You can’t undervalue this skill!
- Conversation is complex

**Designing for Cooperative Conversation**

- [Grice’s maxims](https://www.sas.upenn.edu/~haroldfs/dravling/grice.html)
  - Paul Grice - there are 4 maxims in creating cooperative conversation (i.e. back and forth talk, interesting chat, use of context, rich conversation):
    - Quantity
    - Quality
    - Relation
    - Matter
- Threading
  - Both parties are invested in the conversation
- Implied Context
- Repair
- Acknowledgements and Confirmation

**Tales from the Trenches**

- Anticipate incomplete information
- Be helpful
- Acknowledge and confirm strategically
  - The computer must learn how humans talk
- Find a subject matter expert
- Take a systematic approach
  - Build in the logic
  - Tap the open source community for the spectrum of Utterances (i.e. language cases)
- Always be testing!

**Basic Best Practices**

- Pre-build:
  - Have the right use case
    - Ask, “What is your user trying to do?” + setting and environment
  - Have the right persona
    - NOTE: Not a user persona; but more like personality
  - Build the conversation
- Building the VUI
  - Respect the User
    - How does Alexa’s interactions with the environment affect the user around it
  - This isn’t English class; speak conversationally
  - VUI is not GUI
- Do’s and Don’ts
  - DO
    - Offer a focused experience
    - Validate your experience and utterances
    - Stay cooperative (i.e. the back and forth)
    - Repair the conversation
    - use acknowledgements and confirmation appropriately
    - Have personality
  - DON’T
    - Translate touch to voice - don’t use designing for the web as a model for designing for voice
    - Be rude
    - Lose context of the conversation
    - Turn people into robots


