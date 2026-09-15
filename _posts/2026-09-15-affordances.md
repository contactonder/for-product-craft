---
layout: post
title: "The Metric We've Been Measuring All Along: Affordance"
---

Every SaaS team tracks activation. Most track an aha moment. A growing number track a setup moment, habit moment, or ongoing engagement. These metrics often get treated as separate inventions from separate eras of growth thinking. They are not. They are sequential measurements across a single concept a psychologist named fifty years before product analytics existed.

The concept is **affordance**. It is the exact same framework architects use to design physical spaces, where a bench quietly invites sitting or a wide doorway affords entry. In software, getting it right gives you a clear mental model, the **Affordance Chain**, that reveals what you are actually measuring and tells you which specific fix applies when a growth metric drops.

To understand how this applies to product management today, we have to look at the three evolutionary stages of the Affordance Chain.

### Evolutionary Stage 1: The Ecological Foundation (J. J. Gibson)

James J. Gibson introduced the term over the course of the 1970s, settling it in his 1979 book *The Ecological Approach to Visual Perception*. His definition is precise: an affordance is "what it offers the animal, what it provides or furnishes," a possibility for action that exists in the relationship between a creature and its environment. A set of stairs affords climbing to an adult, but affords nothing to a crawling infant. The stairs do not change. The relationship does.

Gibson insisted affordances exist whether or not anyone notices them. Nature provides direct possibilities for action without needing instructions.

**Affordance Chain: Gibson (Physical Nature)**
1. *Existence:* A sturdy oak branch exists in the forest.
2. *Actualization:* A bird alights on the branch to rest for the first time.
3. *Niche:* The branch becomes the bird's permanent night roosting spot.

### Evolutionary Stage 2: The Design Adaptation (Don Norman)

In 1988 (*The Design of Everyday Things*), Don Norman brought the term into human computer interaction. Unlike nature, digital software hides its codebase behind flat screens. A user cannot directly perceive invisible capabilities without a visual hint.

Norman later clarified this in a 2008 essay titled *"Signifiers, Not Affordances"* in ACM *Interactions*. He introduced **signifiers**, meaning the perceivable cues that reveal an affordance exists. An affordance is the underlying functional capability, but the signifier is the visual clue that tells the user where and how to act.

**Affordance Chain: Don Norman (Digital Interfaces)**
1. *Existence:* The feature exists in the codebase.
2. *Signifier:* The user sees the visual clue or button.
3. *Actualization:* The user tries the action once and receives the payoff.
4. *Niche:* The action becomes a permanent habit.

### Evolutionary Stage 3: SaaS Growth and Retention (Reforge Framework)

When you line Gibson and Norman's work up against modern product analytics, activation stops being a single point on a funnel. Instead, it expands into a five step sequence that maps a user journey from discovery to retention.

**Reforge Framework (SaaS Growth)**
1. *Signed Up:* A team signs up for Slack; the chat channel features exist in the codebase.
2. *Setup Moment:* The admin follows onboarding tooltips to invite three teammates and integrate Google Drive.
3. *Aha Moment:* The team sends their first project update in a channel and gets immediate, real time responses.
4. *Habit Moment:* The team reaches two thousand messages sent over their first thirty days, establishing a regular communication routine.
5. *Engaged State:* The team keeps Slack open on their desktops daily, making it the permanent environment where all work happens.

### Differential Diagnosis: Fixing the Broken Link

Most teams treat a weak activation rate as one vague problem with one default fix, usually redesigning onboarding tooltips. The Affordance Chain gives you a precise differential diagnosis instead, showing you exactly which link in the chain broke:

* **Setup Completion Rate (Signifier Problem):** If users drop off before completing setup, your signifiers or friction are to blame. The affordance exists, but your visual clues fail to guide preparation, or the setup effort outweighs the user's expected reward.
* **Aha Conversion Rate (Actualization Problem):** Of the users who completed setup, how many experienced the core payoff? If setup succeeds but Aha conversion fails, your signifiers worked, but the underlying affordance is not real for this audience, or the payoff is too slow. No tooltip can fix an affordance that does not deliver value.
* **Habit Realization Rate (Early Niche Problem):** Of the users who hit the Aha moment, how many establish a regular cadence? A drop off here means the affordance delivered value once, but failed to become a routine. This is a trigger and re engagement problem, entirely separate from onboarding.
* **Engaged Durability Rate (Niche Decay):** Of the users who built a habit, how many maintain it over recurring quarters? A decline here points to ecological niche decay, meaning the user's underlying needs or external tools shifted, rendering your affordance obsolete.

### The Close

Gibson's core thesis was that a possibility for action means nothing until it is actualized, and it is not stable until it becomes part of how a creature actually lives. 

Product Market Fit (PMF) is not Step 3 of the chain. Experiencing an "Aha moment" once only proves your feature works. True Product Market Fit happens at **Step 4 and Step 5**, the moment your product's affordances stop being features a user occasionally discovers and start being the ecological niche they live inside.

By breaking down the Affordance Chain across its evolutionary stages, you stop throwing generic onboarding overhauls at specific growth bottlenecks. You diagnose the exact link in the chain that broke, and you fix that link alone.
