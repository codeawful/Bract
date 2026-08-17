# Bract Creative Company — Brand Guide

**Status:** Working source of truth  
**Company:** Bract Creative Company  
**Short name:** Bract//CC  
**Primary social handle:** `@bractcc`  
**Last updated:** 2026-08-17

This document captures the current design direction, messaging system, verbal identity, interaction language, social roles, and operating rules for Bract Creative Company. It is intentionally a living guide. Decisions marked as **working direction** can evolve; decisions marked as **core** should remain stable unless there is a deliberate brand change.

---

## 1. Brand foundation

### Core idea

Bract exists to turn worthwhile ideas into things people can see, use, understand, remember, and respond to.

The company should not define itself narrowly as a traditional design agency. The work may include identity, websites, digital experiences, campaigns, creative direction, or other forms depending on what the idea needs.

### Positioning

Bract is an independent creative company working across brand, digital, and creative direction.

The company should feel capable of moving between thinking and making without dividing those activities into artificial agency-language categories. Strategy matters because it improves the work. Craft matters because ideas need form.

### Desired impression

Bract should feel:

- clear
- thoughtful
- confident
- human
- specific
- understated
- curious
- culturally aware without chasing trends

The brand should feel serious enough to trust and relaxed enough to be approachable.

### What Bract is not

Bract should not feel:

- corporate
- self-important
- cryptic
- fashionably vague
- overly poetic
- aggressively sales-driven
- startup-hyped
- like a generic full-service creative agency
- like a brand performing creativity rather than demonstrating it

---

## 2. Messaging hierarchy

Bract uses several short brand lines, but they have different jobs. They should not be stacked everywhere or treated as interchangeable slogans.

### Primary tagline — core

**Made to matter.**

This is the central company tagline.

It expresses the standard for the work rather than the category of work. It can apply to identity, digital products, websites, campaigns, objects, experiences, and future areas of practice without trapping Bract inside one discipline.

### Supporting idea — core

**Ideas made tangible.**

This explains the movement from thinking to making. It works well as positioning language, a capabilities introduction, or a section headline.

### Expressive / campaign line — working core

**Built to be noticed.**

This is outward-facing and more energetic. It should be used selectively for launches, campaigns, project framing, social creative, merchandise, or moments where visibility and distinction are relevant.

### Relationship between the three

A useful mental model is:

1. **Ideas made tangible.** — what we do
2. **Built to be noticed.** — what the work can accomplish
3. **Made to matter.** — why it exists

The sequence can occasionally be used together when a manifesto-like rhythm is appropriate, but it should not become the default presentation.

---

## 3. Verbal personality

### Core voice

Bract writes in a way that is:

**Clear. Conversational. Thoughtful. Confident. Specific. Understated.**

The company should sound like an intelligent person speaking normally, not like a copywriter demonstrating style.

### Most important voice rule

**Never sacrifice natural speech for style.**

If a sentence would sound ridiculous when spoken by a real person, rewrite it.

Restraint should come from editing and clarity, not from removing words until a sentence becomes a fragment.

### Complete thoughts over fragments

Bract should generally use complete sentences in body copy, captions, case studies, emails, and conversational UI.

Avoid using clipped fragments simply to create an “editorial” feeling.

Avoid:

> New work. In progress. Made for the real world.

Prefer:

> We’ve been working on a new identity for the project, and we’ll share the full work soon.

A tagline, navigation label, section label, or button can naturally be short. That is different from making ordinary prose artificially fragmentary.

### Say the specific thing

Prefer:

> We work across identity, websites, digital products, campaigns, and creative direction.

Over:

> We deliver holistic creative solutions for ambitious brands.

### Prefer ordinary words

Use direct verbs such as:

- make
- build
- shape
- find
- see
- notice
- think
- use
- work

Prefer “make” over “facilitate,” “use” over “utilize,” and “change” over “transformation” when the simpler word says the same thing.

### Earn adjectives

Do not call the work bold, innovative, disruptive, meaningful, or unforgettable unless there is a concrete reason to do so.

The work should demonstrate those qualities.

### Do not oversell

Bract should invite people to work with the company rather than chase them.

Confidence comes from presenting the work clearly, explaining decisions when useful, and making contact easy.

### Do not congratulate ourselves

Avoid ceremonial agency announcement language such as:

- “We’re incredibly proud to announce…”
- “We’re beyond excited to share…”
- “We had the amazing opportunity to…”

Prefer beginning with the actual information:

> We worked with ___ to rethink ___. The project started with a simple problem: ___.

### Allow personality without forcing it

Not every line needs to be clever. Most functional copy should be straightforward. A small amount of personality has more impact when the rest of the system is disciplined.

A useful working ratio is roughly **80% clear / 20% expressive**.

---

## 4. Vocabulary

### Words and ideas Bract can build association around

These words naturally fit the company’s worldview and may recur over time:

- make
- made
- matter
- work
- ideas
- form
- things
- notice
- build
- worth
- point
- see
- use
- remember

They should not be forced into every sentence. Repetition over time should create association naturally.

### Language to avoid or use very carefully

- creative solutions
- innovative
- bold
- bespoke
- full-service
- cutting-edge
- impactful
- storytelling
- passionate
- disruptive
- elevate
- empower
- unlock
- leverage
- bring your vision to life
- take your brand to the next level

These terms are not banned because they are inherently wrong. They are avoided because they are heavily commoditized and often make companies sound interchangeable.

---

## 5. Website design direction

**Status: working direction.** The functional prototype established a visual and interaction language worth developing, but typography, exact color values, image direction, spacing tokens, and final component behavior are not yet locked.

### Overall visual character

The site should feel restrained, editorial, tactile, and modern without becoming precious.

Current direction:

- generous whitespace
- strong typographic hierarchy
- large serif display typography paired with a clean sans serif for utility and body copy
- warm light mode rather than stark white
- near-black dark mode rather than a blue-black tech palette
- photography and project imagery used as major visual anchors
- simple rules, grids, and spacing instead of decorative UI
- limited use of accent color unless the identity later establishes one
- motion used to clarify interaction, not as spectacle

### Light and dark mode

The site should support both light and dark appearance modes.

The theme control should sit near the menu control in the global header and should:

- respect the visitor’s system preference on first visit
- allow a manual override
- remember the visitor’s choice
- transition cleanly without a distracting flash

### Navigation

The primary navigation should remain plain and highly legible.

Current core labels:

- Work
- About
- Contact

Capabilities may appear in the menu or within the page depending on final information architecture.

Do not rename basic navigation for personality. A visitor should never have to decode where a link goes.

### Menu interaction

Current preferred direction:

- animated hamburger control
- transforms to a close/X state
- accessible `aria-expanded` behavior
- menu closes with Escape
- backdrop closes the menu
- keyboard navigation remains usable

The animation should be subtle and functional.

### Imagery

Project imagery should carry more visual weight than decorative brand graphics.

The site should favor:

- real work
- close details
- physical material when relevant
- interfaces shown with enough context to understand them
- images that feel composed but not excessively art-directed for their own sake

Avoid filling empty space with generic mockups solely to make the studio look established.

---

## 6. Website message hierarchy

### Hero

**Headline**

> Made to matter.

**Supporting copy**

> We turn ideas into identities, digital experiences, and creative work that people can understand, use, and remember.

**Primary CTA**

> View our work

**Secondary CTA**

> Start a conversation

The two actions serve different visitors: one wants proof first; the other may already be ready to talk.

### Selected work

Use a straightforward section label:

> Selected work

Project navigation should remain literal:

- View project
- View all work
- Next project
- Previous project
- Back to work

### Company explanation

Current working copy:

> We help turn good ideas into things people can actually experience.
>
> Our work can include identity, websites, digital products, campaigns, and creative direction. What we make depends on what the idea needs.

### Capabilities introduction

**Headline**

> Ideas made tangible.

**Supporting copy**

> We work across brand, digital, and creative direction to take an idea from something you can explain to something people can see, use, and respond to.

### Current capability structure

#### Brand

Identity systems, naming, positioning, and visual direction.

#### Digital

Websites, interfaces, and digital experiences.

#### Creative direction

Campaigns, concepts, content, and the systems that hold everything together.

These categories are working structure rather than permanent organizational boundaries.

### Closing contact section

**Headline**

> Have something worth making?

**Supporting copy**

> Tell us what you’re working on, what you need, and where you’d like to take it.

**CTA into contact flow**

> Start a conversation

**Form submission button**

> Send inquiry

The distinction is intentional: “Start a conversation” invites the user into the contact experience; “Send inquiry” tells them exactly what the form button does.

---

## 7. CTA system

Bract uses three levels of call-to-action language.

### Level 1 — functional

Use clear labels when the user is navigating or completing an obvious task.

Preferred examples:

- View our work
- View project
- View all work
- About us
- Contact
- Read more
- Next project
- Previous project
- Back to work
- Send inquiry

Do not make simple actions clever.

### Level 2 — conversational

Use these when inviting a relationship or inquiry.

Primary default:

> Start a conversation

Other approved directions:

- Tell us about your project
- Tell us what you’re working on
- Let’s talk about it
- Send us a note

### Level 3 — expressive

Use sparingly in social, campaigns, experiments, or other contexts where the audience already understands what is happening.

Examples:

- What are you making?
- Show us what you’re working on.
- Have something worth making?
- What should we make next?
- Want to make something together?

### CTA principle

**Invite early, reassure in the middle, ask clearly at the end.**

The website should make it easy to contact Bract throughout the experience without turning into a sales funnel.

---

## 8. Contact and form language

### Contact principle

Bract should communicate availability without pressure.

The underlying attitude is:

> If you have something interesting to make, we’re interested in hearing about it.

### Form introduction

> Tell us what you’re working on, what you need, and where you’d like to take it.

### Success message

Preferred:

> Thanks for telling us about it. We’ll take a look and get back to you soon.

Alternative:

> Thanks for getting in touch. We’ll read through what you sent and get back to you soon.

### Error message

> Something didn’t go through. Please try again, or send us an email instead.

Avoid generic system language such as “Your submission has been received” when a natural sentence works better.

---

## 9. Social identity

### Core profile identity

**Company:** Bract Creative Company  
**Short name:** Bract//CC  
**Handle:** `@bractcc`  
**Tagline:** Made to matter.  
**Supporting phrase:** Ideas made tangible.

### Platform roles

The same company should not become five identical feeds.

#### Instagram

**Role:** visual work, process, studio material, project presentation, selective conversation.

Working bio:

> We turn ideas into identities, digital experiences, and creative work.  
> Made to matter.

#### X / Twitter

**Role:** thinking, making, observations, conversation, links, project notes.

Working bio:

> We make identities, digital experiences, and other things worth making.

#### Threads

**Role:** the most conversational expression of the brand; questions, observations, interaction with other makers.

Working bio:

> We make things, notice things that are made well, and talk to people who make things too.

#### LinkedIn

**Role:** business-facing credibility, client work, project reasoning, company updates, industry perspective.

Working short line:

> Ideas made tangible.

Working About copy:

> Bract is an independent creative company working across identity, digital experiences, and creative direction.
>
> We help turn good ideas into things people can actually experience. What we make depends on what the idea needs.
>
> Made to matter.

#### Behance

**Role:** deeper project presentation and portfolio discovery.

Working short bio:

> An independent creative company working across brand, digital, and creative direction.

Working profile statement:

> We turn ideas into identities, websites, digital experiences, campaigns, and other things people can see, use, and remember.
>
> Made to matter.

### Account ownership priority

Current active / priority ecosystem:

- Instagram — `@bractcc`
- X / Twitter — `@bractcc`
- Threads — claim/use `@bractcc`
- LinkedIn — Bract Creative Company; secure the company vanity name where possible
- Behance — secure/use `bractcc`

Reserve when practical:

- Bluesky
- YouTube
- TikTok
- Pinterest
- Facebook
- Dribbble

Owning the identity does not create an obligation to publish actively on every network.

---

## 10. Social voice and behavior

### Core principle

**The website converts. Social converses.**

The website should calmly help people understand Bract and contact the company. Social should give people a reason to interact with Bract even when they are not currently looking to hire a creative company.

### Relationship to making

Bract should not only talk about what Bract makes. It should be interested in people who make things.

This creates a broader cultural role:

- Bract makes things.
- Bract notices things that are made well.
- Bract talks to other people who make things.

### Ask questions worth answering

Avoid engagement bait.

Avoid:

- “Designers, what do we think? 👀”
- “Drop a 🔥 if you agree.”
- manufactured hot takes
- questions that exist only to farm replies

Prefer questions that can start actual conversation, for example:

> What’s a piece of design you still remember years after seeing it?

### Working recurring content territories

These are content systems, not mandatory posting schedules.

#### What are you making?

Community-oriented questions about work, ideas, experiments, and process.

#### Worth noticing

Bract shares something made by someone else and explains specifically why it deserves attention.

#### Made by

A format for highlighting Bract work, collaborators, or other makers with enough context to make the feature meaningful.

The company should not force these labels onto every post. They are recurring territories that can make the social presence recognizable over time.

---

## 11. Announcing work

Bract should not use exaggerated launch language.

Avoid:

> We’re beyond excited to finally unveil our latest incredible collaboration with…

Prefer:

> We worked with ___ to rethink ___. The project started with a simple problem: ___.

Or:

> ___ came to us with ___. We helped turn it into ___.

Explain the work in plain language. Let the project provide the excitement.

---

## 12. Editorial behavior

### Case studies

Case studies should explain enough to make the work intelligible without narrating every design decision.

A useful structure is:

1. What the client or project needed
2. What Bract believed the real problem was
3. What Bract made
4. Why key decisions were made
5. What changed or became possible

Avoid inflating ordinary project steps into strategic breakthroughs.

### Captions

Captions should read like someone from the company wrote them because they had something useful to say, not because the content calendar required copy.

### Emails

Bract email should be professional, concise, and conversational. Do not import tagline language into routine correspondence unless it is part of a formal signature or campaign.

### System messages

System copy should prioritize clarity first and personality second.

---

## 13. Brand rules — quick reference

### Do

- Write complete thoughts.
- Use normal human language.
- Be specific.
- Explain what matters and remove what does not.
- Let the work demonstrate taste.
- Keep navigation and functional UI clear.
- Invite conversation without pressure.
- Give project work enough context to be understood.
- Notice and share good work made by other people.
- Use short brand lines selectively.

### Don’t

- Write fragments merely to appear editorial.
- Treat copy like poetry or song lyrics.
- Stack slogans everywhere.
- Use generic agency language.
- Turn every button into a joke.
- Congratulate Bract for doing ordinary professional work.
- Overstate results or significance.
- Use social only as a portfolio broadcast channel.
- Chase engagement with empty prompts.
- Confuse visual restraint with emotional coldness.

---

## 14. Current decisions vs. open decisions

### Considered core for now

- Bract Creative Company
- Bract//CC as the short visual name
- `@bractcc` as the social handle
- **Made to matter.** as the primary tagline
- **Ideas made tangible.** as the supporting idea
- **Built to be noticed.** as an expressive/campaign line
- clear, conversational, complete-sentence writing
- restrained website navigation
- “Start a conversation” as the default inquiry CTA
- “Have something worth making?” as the closing contact headline
- social as conversation rather than pure broadcasting

### Working direction, not yet locked

- final logo and mark system
- whether `B//CC` becomes the social avatar or another mark is developed
- exact typography
- exact color palette
- photography/art-direction rules
- final website spacing and grid system
- final homepage architecture
- final capability naming
- final domain and email system
- final social launch content and cadence
- whether Bract develops recurring editorial properties beyond social posts

---

## 15. Decision test

When evaluating future copy, design, or content, ask:

1. Is it clear?
2. Would a real person actually say this?
3. Is it specific enough to mean something?
4. Is it doing a job, or merely trying to look creative?
5. Does it feel confident without overselling?
6. Does the interaction remain obvious?
7. Does it help Bract make, explain, or share something that matters?

If a choice fails several of these questions, revise it.

---

## 16. Working brand summary

Bract Creative Company turns ideas into identities, digital experiences, and creative work that people can understand, use, and remember.

The company communicates with restraint, but it does not speak in fragments or artificial editorial shorthand. It uses complete thoughts, normal words, and enough context to be useful. Its website is calm and clear. Its social presence is more conversational and interested in the wider culture of making.

Bract does not need to continually tell people it is creative. The quality of the work, the precision of the language, and the way the company behaves should make that apparent.

**Made to matter.**
