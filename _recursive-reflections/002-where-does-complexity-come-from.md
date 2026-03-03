---
layout: blogpost
title: "001 — When Humans Begin to Count?"
date: 2026-02-02
tags: [numbers, history, patterns]
---

# Where Does Complexity Come From?

I keep returning to the same question.

Where does complexity come from?

Not complexity in equations.  
Not symbolic complexity.

Complexity in the world.

The branching of a river delta.  
The spiral of a shell.  
The way a flock of starlings folds into itself and then opens again — like breath.

No one designs these things.  
No architect drafts a snowflake.  
No choreographer directs a murmuration.

And yet what appears is structured. Geometric. Sometimes so precise it feels intentional.

I used to assume complexity required design.

Now I’m not so sure.

---

## The Starlings

The first time I watched a murmuration carefully, something shifted.

Thousands of birds. No visible leader.

And yet the flock moves as if it shares a single nervous system.

I watched this clip again recently:

https://www.youtube.com/watch?v=V4f_1_r80RY  

I forced myself not to romanticize it.

Instead, I asked:

What rule could each bird be following?

Just one bird.

What information does it have?  
Only its nearest neighbors.  
Only local signals.

If that’s true, then the global shape isn’t designed.

It emerges.

That word keeps returning.

Emerges.

---

## The Fireflies

Then I learned about synchronous fireflies in Southeast Asia — entire trees lighting up in perfect rhythm along mangrove rivers.

https://www.youtube.com/watch?v=O7lZ7t7V3M8  

Each firefly has its own internal timing.

But when one flashes, nearby fireflies adjust slightly.

Tiny adjustments.

Over time, the whole system synchronizes.

No master clock.

Just interaction.

It unsettled me.

Maybe complexity isn’t planned.

Maybe it’s negotiated.

---

## When I Tried to Make Randomness

At some point, I decided to strip everything down.

If complexity emerges from rules, what does pure randomness look like?

So I wrote the simplest thing I could:

```javascript
for (let i = 0; i < 10000; i++) {
  let x = random(width);
  let y = random(height);
  point(x, y);
}