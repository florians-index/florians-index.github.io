---
layout: default
title: Entering Pipes
nav_order: "6"
parent: Basic Game Information
permalink: /pipes
---
# Entering Pipes

Entering warp pipes might seem like something not worth bringing up, but there is a bit more nuance to it than you may think.

For horizontal pipes... yeah, there's not much going on here. Come in one side, come out the other. If you are able to execute a **pipe kick** (wall kick after leaving a floating horizontal pipe), then you should do so, however with Jet Run it makes a very minimal difference.

On the other hand. **vertical pipes require slightly more thought.** The reason you can do this is because *you can enter a vertical pipe in two different ways:
- Pressing crouch on top of a pipe
- Ground pounding into a pipe

Despite the animation of starting it up, ***ground pounding into vertical pipes IS faster than crouching on top of them***.

This is especially important in Elephant form, where the normal pipe animation is slower.

Below is a comparison showcasing the differences between the two, with and without Elephant.

<video controls width="100%">
  <source src="{{ '/assets/videos/pipecomp.mp4' | relative_url }}" type="video/mp4">
</video>

#### Cycle Preservation

While ground pounding into pipes is almost always faster, there *is* a very niche use for normally entering pipes, especially if you are a beginner.

While most cycles in this game start when the moving elements are close to being rendered, some start on level load and don't reset on pipe transitions. This means your pipe entry contributes to whether or not you can make a certain cycle.

Oh well, that just means it's even more important to ground pound into them right? Well, not exactly.

Even though normally entering pipes is slower, **the game elements freeze in place during the animation, while ground pounding does not.**

This allows you to ***sacrifice REAL time to make up IN-GAME time to make a cycle easier to catch.***

A notable example for this is in the level **Raaarghs in the Ruins**, where there is a relatively tight cycle to make during the Wonder Section that starts moving as soon as you enter the level. You have to move through the level very well to make it, and missing it loses around 7s.

If you're struggling to hit the optimal Raaarghs cycle, **try normally entering the pipe instead of ground pounding, as that gives you more time to work with.** The minimal timeloss from an unoptimal pipe entry is worth it to save the time on the optimal cycle if you can't make it without it.