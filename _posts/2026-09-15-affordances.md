---
layout: post
title: "The Metric We've Been Measuring All Along: Affordance"
---

Every SaaS team tracks activation. Most track an aha moment. A growing number track a setup moment, habit moment, or ongoing engagement. These metrics often get treated as separate inventions from separate eras of growth thinking. They aren't. They are measurements across the life cycle of a single concept a psychologist named fifty years before product analytics existed.

The concept is **affordance**. Getting it right clarifies what you measure and—more usefully—tells you which specific fix actually applies when a number looks bad.

### What Gibson Actually Meant

James J. Gibson introduced the term over the course of the 1970s, settling it in his 1979 book *The Ecological Approach to Visual Perception*. His definition is precise: an affordance is "what it offers the animal, what it provides or furnishes," a possibility for action that exists in the relationship between a creature and its environment. A set of stairs affords climbing to an adult. It affords nothing to a crawling infant. The stairs don't change. The relationship does.

The detail most product people miss: Gibson insisted affordances are real whether or not anyone notices them. A feature that would genuinely help a user is an affordance the moment it exists in your product, regardless of whether that user has ever seen it.

### Norman's Correction, and His Own Regret About It

In 1988, Don Norman brought the term into design with a shift: he cared about *perceived* affordances—what a user believes is possible, not what's objectively true. A button that works but doesn't look clickable has an affordance nobody can use.

Norman later admitted this created exactly the confusion you'd expect from renaming someone else's concept. In a 2008 essay he introduced a cleaner term for what he'd actually meant: **signifiers**, the visible cues that reveal an affordance exists. His own verdict on the term he'd popularized twenty years earlier: "designers of the world, forget affordances, provide signifiers."

That's not a footnote. It's the whole diagnostic tool.

### Five States, One Unifying Theory

If you map these ideas onto standard growth frameworks (like Reforge’s user lifecycle model), "Activation" stops being a single point on a funnel and reveals itself as an overarching process spanning from signup to habit formation. Across those stages, Gibson's affordance theory provides an exact blueprint for what is happening at each state:

1. **Signed Up (Entering the Environment):** The user enters the product environment. Affordances exist objectively in your code, but none have been perceived or actualized yet.
2. **Setup Moment (Signifiers and Preparatory Action):** The user performs the necessary actions—connecting an integration, inviting a teammate, configuring a setting—to prepare for the core value. This is driven entirely by signifiers guiding the user through necessary environmental friction before any value is delivered.
3. **Aha Moment (Actualizing the Affordance):** The affordance is actualized for the first time. The user takes the core action and receives the immediate payoff Gibson described—a real possibility, acted on and confirmed.
4. **Habit Moment (Early Niche Formation):** The user repeats the core action with sufficient frequency to establish a habit. In Gibsonian terms, this is early *niche formation*—the affordance begins to form a stable structure in the user's routine.
5. **Engaged State (The Sustained Ecological Niche):** Gibson described a species' set of reliable affordances as its *ecological niche*: the stable structure of possibilities an animal actually lives inside. The Engaged state is the niche fully realized over time— sustained, repeatable value realization within a defined window.

### Differential Diagnosis: The Part That Actually Matters

Most teams treat a weak activation rate as one problem with one fix—usually adding more onboarding tooltips. Reframing the funnel through affordances gives you a precise differential diagnosis instead:

* **Discovery & Setup Completion Rate:** Measure how many signed-up users discover and successfully complete setup actions. If users drop off here, you have a **signifier or friction problem**. The affordance exists, but the cues guiding preparation are poor, or the preparatory effort outweighs perceived potential value.
* **Aha Conversion Rate (Conditional on Setup):** Of the users who completed setup, how many experienced the core payoff? If setup completes but Aha conversion fails, your signifiers worked, but the underlying affordance isn't real for this audience—or the payoff isn't landing fast enough. No amount of tooltips fixes an affordance that doesn't deliver value.
* **Habit Realization Rate:** Of the users who hit the Aha moment, how many establish the core habit frequency? A gap here means the affordance was real and experienced, but failed to transition into early niche formation. This is an engagement trigger and re-engagement problem, completely separate from setup or discovery.
* **Engaged Durability Rate:** Of the users who reached the habit moment, how many maintain that habit over defined recurring time windows? A decline here indicates ecological niche decay—the user's environment or workflows shifted, making the affordance obsolete or secondary to new alternatives.

### The Close

Gibson's core thesis was that a possibility for action means nothing until it is taken up, and it isn't stable until it becomes part of how a creature actually lives. Product-market fit, measured honestly, is the moment your product's affordances stop being features a user discovers and start being the ecological niche they live inside.

By separating existence from signifiers, and initial actualization from sustained niche behavior, you stop throwing generic onboarding redesigns at specific growth bottlenecks. You fix the precise link in the affordance chain that broke.
