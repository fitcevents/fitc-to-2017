# Styling Hilary
Focus of the presentation:
How I built a design system used by dozens of apps
How I implemented redesign of hillaryclinton.com

**The Story of Pantsuit**

- Kyle Rush, Deputy CTO, Hillary for America: “We need a Bootstrap and it needs a good name…”
  - Mina: Naming things is hard…
    - Pattern Library - Library of UI patterns (e.g. UI kit)
    - Framework - The front-end code
    - Style Guide - The documentation for the CSS framework
    - Design system - All of the above (see Nate Baldwin’s “Anatomy of a Design System”)
- Mina was not at all convinced why it should be named “Pantsuit”
- Why build a design system?
  - hillaryclinton.com is a very large and prolific piece of engineering
    - E.g. hillaryclinton.com/donate had a different codebase (also hillaryclinton.com/calls)
  - We had multiple codebases. And needed one UI.
- The Pantsuit team… was just me. I had to make a lot of decisions myself (especially those of time and speed)
  - DONE is better than perfect
  - “If we don’t ship on time, the ship will have sailed” - Stephanie Hannon, CTO
- Pantsuit 1.0 was built in 6 weeks
  - Technical debt becomes your friend
  - As time progressed, maintainability went down and stability went up
  - MORAL: If you don’t have technical debit, you’re not moving fast enough.

**How Pantsuit was Built**

- First version was a code rewrite
  - Did a CSS Audit of the entire site to identify opportunities for refactoring
  - Did a UI Audit, i.e. inventory of the visual elements (e.g. navigation, buttons, headings)
- Building Pantsuit 2.0
  - (Re)define - Implement - Test - Iterate
    - Define what the components are
      - Given a page, look for repeating patterns
      - Learned that I needed to separate the semantic name and the class heading
      - She translated the UI elements into CSS
    - Implement (i.e. Code it live)
      - Constant back and forth among Framework, Product, and UI Kit
    - Test and Iterate
      - As I was building the site, I was repeatedly checking for accessibility (using WAVE)
      - Accessibility testing revealed that the site had focused states but not have hover states
      - Had to strike compromises with visual design in the name of accessibility 
- Mina: I sought out as much collaboration as possible
  - Through the “Pantsuit Council”
  - Decided to document AS MUCH as possible
- “The documentation for Pantsuit is a great example of form following function: it served as a source of inspiration as well as a how-to” - Beth Andres-Beck, Senior Fundraiser

**Outcomes**

- Developers felt Pantsuit was the best tool they had ever had
- HRC was excited about the design system too
- Harassment
  - “I doubt that she wrote it herself”
  - Fake News - misinformation.

