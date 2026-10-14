---
layout: post
title: 'The Honesty Paradigm in Agentic Design'
---

In the 1970s, industrial designer Dieter Rams set down ten principles for good design. The sixth principle is the quietest one: good design is honest. It does not make a product appear more innovative, powerful, or valuable than it actually is. It does not try to manipulate the consumer with promises the object cannot keep.

For decades, software craftsmanship treated honesty as a matter of copy and pricing. You did not put fake countdown timers on checkout pages, and you did not hide cancellation buttons behind support phone lines. The interface itself was mostly neutral. A button was a button. A text box was a text box. The software did what the code instructed, no more and no less.

In the agentic era, that neutrality has vanished. We are now building systems that simulate reasoning, take autonomous action, and speak with human politeness. In doing so, we have created a new kind of dishonesty: the illusion of certainty.

## The Performed Certainty of AI Agents

When an AI agent takes an input, it does not experience doubt. It generates text based on probabilities. Yet the interfaces we wrap around these models are almost always designed to project total composure.

Imagine an agent asked to summarize a forty page vendor contract. It returns a clean, confident summary with tidy headings and complete sentences. Buried on page thirty one is an unusual clause: the vendor can raise prices by 30% with only two weeks of notice. The agent did not flag it. It did not say it was unsure whether that clause mattered. The summary looked finished, so the manager signed. Nobody saw the problem until the first invoice arrived.

This is **Performed Certainty**: an interface that looks sure of itself whether or not it has earned that look.

It is a failure of craftsmanship. It is the digital version of building a radio out of cheap plastic painted to look like brushed aluminum. The surface lies about the strength of what sits beneath it.

## The Friction of Admitting What You Do Not Know

Traditional software design spent fifteen years removing friction. We celebrated one click actions, zero state onboarding, and background automation. We treated every modal, warning box, and confirmation step as a flaw to be optimized away.

When software becomes agentic, removing friction without establishing honesty is dangerous. When an agent acts on behalf of a user, an invisible failure is far worse than a visible delay.

<table style="width: 100%; border-collapse: collapse; margin: 24px 0; font-size: 0.95rem;">
  <thead>
    <tr style="border-bottom: 2px solid #ddd; text-align: left;">
      <th style="padding: 10px; width: 30%;">Design Approach</th>
      <th style="padding: 10px; width: 70%;">What the Agent Does</th>
    </tr>
  </thead>
  <tbody>
    <tr style="border-bottom: 1px solid #eee;">
      <td style="padding: 10px;"><strong>Performed Certainty</strong></td>
      <td style="padding: 10px;">Hides its doubt behind polite, definitive prose and clean layouts. Errors surface only after the action is complete.</td>
    </tr>
    <tr style="border-bottom: 1px solid #eee;">
      <td style="padding: 10px;"><strong>Honest Design</strong></td>
      <td style="padding: 10px;">Shows how sure it is, flags the steps where it guessed, and asks for human approval before changes that are hard to undo.</td>
    </tr>
  </tbody>
</table>

Honest agent design means bringing back deliberate, strategic friction. If an agent is unsure about a data extraction step, the interface should look unsure. It should highlight the ambiguity in yellow, show the source document side by side, and ask a human to verify the inference before continuing.

## A Hard Problem: How Does the Agent Know?

There is an obvious objection. How can an agent say "I am forty percent sure" when language models do not produce a reliable confidence number?

This is a real challenge. The internal probabilities of a model are often **poorly calibrated**. (Calibration means that when a system says "80% sure," it is right about 80% of the time.) A confidence score shown on screen can become another form of performed certainty, a precise looking number with nothing solid behind it.

So good design should not depend on one magic number. It should combine practical signals:

* **Sources:** Can the agent point to the exact passage that supports its claim?
* **Consistency:** Does the agent give the same answer when it runs the task several times?
* **Reversibility:** If the agent is wrong, can the action be undone?
* **Coverage:** Did the agent read the whole input, or did part of it fall outside its limits?

None of these signals is perfect. Together, they are far more honest than a confident tone of voice.

## Designing the Confidence Spectrum

How do you apply Rams' principle to an agentic workflow? You make confidence a visible part of the interface. But confidence alone is not enough. You need to ask two questions at the same time:

1. **How sure is the agent?**
2. **How costly is a mistake?**

A low confidence guess that fixes a typo is harmless. A high confidence action that deletes customer records is not. The right amount of friction depends on both answers.

<table style="width: 100%; border-collapse: collapse; margin: 24px 0; font-size: 0.95rem;">
  <thead>
    <tr style="border-bottom: 2px solid #ddd; text-align: left;">
      <th style="padding: 10px; width: 20%;"></th>
      <th style="padding: 10px; width: 40%;">Low Cost of Error</th>
      <th style="padding: 10px; width: 40%;">High Cost of Error</th>
    </tr>
  </thead>
  <tbody>
    <tr style="border-bottom: 1px solid #eee;">
      <td style="padding: 10px;"><strong>High Confidence</strong></td>
      <td style="padding: 10px;"><strong>Act.</strong> The agent proceeds and keeps a log that can be audited later.</td>
      <td style="padding: 10px;"><strong>Confirm.</strong> The agent shows its sources and waits for one approval click.</td>
    </tr>
    <tr style="border-bottom: 1px solid #eee;">
      <td style="padding: 10px;"><strong>Low Confidence</strong></td>
      <td style="padding: 10px;"><strong>Draft.</strong> The agent proceeds, but marks its assumptions so a human can review them.</td>
      <td style="padding: 10px;"><strong>Hand off.</strong> The agent stops, explains where it broke down, and asks the exact question a human must answer.</td>
    </tr>
  </tbody>
</table>

This also answers a second objection. If you add too many approval steps, users stop reading them and click "approve" automatically. This is called **alert fatigue** (people ignore warnings when they see too many). The matrix helps because friction appears only where it matters. Most actions flow freely. The few that need a human mind are clearly marked, so people take them seriously.

When a team designs this way, it builds a product that respects the user's intelligence. It stops pretending the model knows everything.

<div style="margin: 40px auto; max-width: 450px; text-align: center; border: 1px solid #eee; padding: 15px; border-radius: 4px; background: #fafafa;">
  <img src="{{ site.baseurl }}/images/agentic_honesty_framework.png" alt="Agentic Honesty Framework" style="width: 100%; height: auto; border-radius: 2px;">
  <p style="margin: 10px 0 0 0; font-size: 0.85rem; color: #666; font-style: italic;">
    The Confidence Spectrum: matching interface friction to confidence and consequence.
  </p>
</div>

## Trust Is Built on Exposed Weakness

The temptation in product management is always to make the technology look more capable than it is. We want smooth demos where the agent does the whole job from start to finish without a single hitch.

That habit worked when software was deterministic. (Deterministic means the same input always gives the same output.) It fails when software is probabilistic, because the output can be wrong in ways nobody predicted.

When an agent hides its uncertainty and fails silently, the user loses faith in the entire system. When an agent shows its work and its sources, admits where it is unsure, and asks for help at the right moment, the user feels in control.

Dieter Rams understood that good design does not decorate an object. It reveals its true nature. In the agentic era, revealing the true nature of software means being honest about what the machine knows, what it guessed, and where it needs a human mind to finish the work.
