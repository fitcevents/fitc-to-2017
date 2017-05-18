# How We Built a Bot for FITC
Rami Sayar
@ramisayer

Chatbots can great for all kinds of things, from silly to serious.

- law bot built by a 19 year old to help you fight parking tickets
- Murphy bot, Microsoft demo that handles “what if” scenarios
- Microsoft Xiaoice a chatbot on Weibo with 850k followers that was even incorporated into a news show

Are bots hype? Why now?
Mobile is the new dominant form factor. These devices have contact books and a phone number as your unique identifier. They also have photos and push notifications. These things, plus always on connectivity make them the ideal devices for chat bots to thrive. Also, the most used apps on people’s phones tend to be messenger apps.


- Bots don’t require downloading app updates
- They can solve many of the problems that apps are currently used for, with less friction
- Conversational UI is easy to understand
- Rapid growth of natural language processing, AI and machine learning are powerful tools for providing understanding of the user’s intent

Just don’t built Clippy!

There are a range of bots that fall on a range of “fun” to “functional” - the FITC app falls in the middle, needs to provide answers to questions and send Shawn cats.

Microsoft’s bot connective service allows your bot to run on a number of different platforms. 

- it routes the message from the chat app, standardizes the message format and sends it to your code
- BotFramework provides APIs in C# or Node.js to talk to many of Microsoft’s services 

Bot code is structured around the notion of a dialog:

- conversation has a beginning and an end
- dialogs can branch to others
- multiple dialog types:
  - prompts
  - natural language processing
  - profiles
  - forms
- can send an attachment (location, image, etc) to the bot or the bot can return attachments
- display results in pre-formatted card types hero/thumbnail, receipts, etc

When developing bots you can initially communicate with them via console. Can also run them locally in Microsoft’s Bot Emulator.

Microsoft has a long list of Cognitive Services that you can communicate with over REST APIs. These include:

- LUIS (Language Understanding Intelligence Service)
- Vision API for understanding what’s in a photo
- Face API can identify faces, match faces, etc
- Emotion APIs can understand what emotion a user is showing in a picture
- QnA Maker

QnA Maker used for FAQ section of FITC Bot. Provide it a csv of questions and answers. API will try and understand a question and find the best match in the QnA Maker.

What makes a bot great?
Not necessarily how intelligent it is, but how well it solves the needs of the user. 

How does a bot react in crisis?
Important to consider how a bot handles less than best case scenario. 

Common Problems:
The “mysterious bot” - not clear how it works or what to do
The “stubborn bot” - keeps asking the same question over and over
The “bot that can’t forget” - can’t forget a detail it was given earlier even though it was told to
The “clueless bot” - doesn’t seem to answer any of the questions given to it



