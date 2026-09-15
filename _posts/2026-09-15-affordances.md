---
layout: post
title: "The Metric We've Been Measuring All Along: Affordance"
---

Every SaaS team tracks activation. Most track an aha moment. A growing number track a setup moment, habit moment, or ongoing engagement. These metrics often get treated as separate inventions from separate eras of growth thinking. They are not. They are sequential measurements across a single concept a psychologist named fifty years before product analytics existed.

The concept is **affordance**. Getting it right gives you a clear mental model (the **Affordance Chain**) that reveals what you are actually measuring and tells you which specific fix applies when a growth metric drops.

### What Gibson Actually Meant

James J. Gibson introduced the term over the course of the 1970s, settling it in his 1979 book *The Ecological Approach to Visual Perception*. His definition is precise: an affordance is "what it offers the animal, what it provides or furnishes," a possibility for action that exists in the relationship between a creature and its environment. A set of stairs affords climbing to an adult. It affords nothing to a crawling infant. The stairs do not change. The relationship does.

The detail most product people miss: Gibson insisted affordances exist whether or not anyone notices them. A feature that would genuinely help a user is an affordance the moment it exists in your product codebase, regardless of whether that user has ever seen it.

### Norman's Correction, and His Own Regret About It

In 1988 (*The Design of Everyday Things*), Don Norman brought the term into design with a shift: he cared about *perceived* affordances, meaning what a user believes is possible, not what is objectively true. A button that works but does not look clickable has an affordance nobody can use.

Norman later admitted this created exactly the confusion you would expect from renaming someone else's concept. In a 2008 essay titled *"Signifiers, Not Affordances"* (published in ACM *Interactions*), he introduced a cleaner term for what he had actually meant: **signifiers**, meaning the visible cues that reveal an affordance exists. His own verdict on the term he had popularized twenty years earlier: *"Designers of the world: Forget affordances. Provide signifiers."*

That is not a footnote. It is the whole diagnostic tool.

### The Affordance Chain: Five States of User Action

When you line these concepts up against standard SaaS growth frameworks, like the Reforge retention model, activation stops being a single point on a funnel. Instead, it expands into a five step sequence (the **Affordance Chain**) that maps a user journey from discovery to retention:

1. **Signed Up (Existence):** The user enters the environment. Affordances exist objectively in your code, but none have been perceived or acted on yet.
2. **Setup Moment (Signifiers and Preparation):** The user takes preparatory actions, such as connecting an integration, inviting a teammate, or configuring a setting, guided entirely by visual clues (**signifiers**). They have not received value yet. They are simply following the clues to prepare the environment.
3. **Aha Moment (Actualization):** The affordance is actualized for the first time. The user clicks the key button, runs the core workflow, and experiences the value payoff for the first time.
4. **Habit Moment (Early Niche Formation):** The user repeats the core action with enough frequency that it begins to form a routine. In Gibson's terms, this is early *niche formation*, meaning the affordance starts becoming a stable pattern in their workflow.
5. **Engaged State (The Sustained Niche):** Gibson described a species' set of reliable affordances as its *ecological niche*: the environment an animal permanently lives inside. The Engaged state is the niche fully realized, meaning sustained, repeated reliance on your product over extended time windows.

### Differential Diagnosis: Fixing the Broken Link

Most teams treat a weak activation rate as one vague problem with one default fix, usually redesigning onboarding tooltips. The Affordance Chain gives you a precise differential diagnosis instead, showing you exactly which link in the chain broke:

* **Setup Completion Rate (Signifier Problem):** If users drop off before completing setup, your signifiers or friction are to blame. The affordance exists, but your visual clues fail to guide preparation, or the setup effort outweighs the user's expected reward.
* **Aha Conversion Rate (Actualization Problem):** Of the users who completed setup, how many experienced the core payoff? If setup succeeds but Aha conversion fails, your signifiers worked, but the underlying affordance is not real for this audience, or the payoff is too slow. No tooltip can fix an affordance that does not deliver value.
* **Habit Realization Rate (Early Niche Problem):** Of the users who hit the Aha moment, how many establish a regular cadence? A drop off here means the affordance delivered value once, but failed to become a routine. This is a trigger and re-engagement problem, entirely separate from onboarding.
* **Engaged Durability Rate (Niche Decay):** Of the users who built a habit, how many maintain it over recurring quarters? A decline here points to ecological niche decay, meaning the user's underlying needs or external tools shifted, rendering your affordance obsolete.

### The Close

Gibson's core thesis was that a possibility for action means nothing until it is actualized, and it is not stable until it becomes part of how a creature actually lives. 

Product Market Fit (PMF) is not Step 3 of the chain. Experiencing an "Aha moment" once only proves your feature works. True Product Market Fit happens at **Step 4 and Step 5**, the moment your product's affordances stop being features a user occasionally discovers and start being the ecological niche they live inside.

By breaking down the Affordance Chain, you stop throwing generic onboarding overhauls at specific growth bottlenecks. You diagnose the exact link in the chain that broke, and you fix that link alone.
