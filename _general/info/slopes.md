---
layout: default
title: Slopes
nav_order: "3"
parent: Basic Game Information
permalink: /slopes
---
# Slopes

Slopes are a staple to the 2D Mario series, offering more variety in level designs instead of relying on flat straightaways. If you're familiar with speedrunning 2D Mario games, you'll know how important it is to understand how they impact your speed and movement decisions.

This section goes *quite* in-depth and technical deep dive into slopes in SMBW, and might seem confusing to some. ***Read the TL;DR at the end of this page if you do NOT care about technical details and just want a basic summary***

When discussing the size of slopes, they are described as **width x height**. For example, a *2x1* slope is a slope that is 2 blocks wide, and 1 block tall.

#### General Information

For starters, let's discuss **upward slopes**, which are the easiest to explain.

You want to **always** jump over upward slopes, as your speed is slower going uphill. Might be common sense to some, but still worth a small mention.

Now, for the rest of this section we'll be discussing **downward slopes**.

Secondly, just like in the NSMB series, you can *slide down slopes* by crouching while on the slope. 

You will see this being done in NSMB runs to gain additional speed on downward slopes, but that is actually ***NOT*** the case in SMBW. You want to avoid sliding down slopes as it is strictly slower to do so. Instead, you should opt to **run down slopes instead**.

However, this isn't the full picture...

In SMBW, there is 2 types of slopes: **shallow** and **steep**

**Shallow**: Slopes that are twice as *wide* as they are *tall* - Examples: 2x1, 4x2, 6x3
**Steep**: Slopes that are as *wide* as they are *tall* - Example: 1x1, 2x2, 3x3

The size of the slope (and current badge equipped) will dictate whether or not you should either:
- Run down the slope
- Avoid or jump over it

Let's discuss the specifics.

#### No Speed Badge (Badgeless)

With no speed badge equipped, the only slopes you want to run down are *long, shallow slopes.*

Being specific: ***Run down all shallow slopes EXCEPT 1x1 or 2x1 slopes**.*

To avoid overcomplicating this explanation, your top speed is higher on a slope to account for the extra distance you are covering, but you still need to *accelerate* to that speed, so that is why short slopes are slower.

The reason you save time on longer shallow slopes is because the top speed increase overcompensates for the extra distance, making you faster overall.

Your top speed on steep slopes does not overcompensates for the extra distance, so it's better to avoid them.

#### Jet Run (Crouch Boost)

With the Jet Run badge, slope interactions change slightly.

The general idea still applies, except with Jet Run you have an exclusive (and relatively advanced-level) technique at your disposal: **crouch boosts**

Because your character *decelerates slower while crouching*, if you crouch the frame after running down a slope (the frame your character is back on flat ground), you can **preserve your faster top speed from the slope for longer than normal**.

This makes it ***worth to run down EVERY slope with Jet Run, to get an opportunity to crouch boost***.

A perfect crouch boost saves *approximately*:
- Shallow Slope: **0.033s** with a **0.35s** crouch
- Steep Slope: **0.1s** with a **0.5s** crouch

Once again, these are approximations also assuming a **frame perfect** crouch, however the saving grace is that crouch boosts **do not lose time to execute if you react accordingly**. For example, if you crouch too early and slide down, jump immediately to go back to running. A slightly later crouch will still result in some speed conservation, but you must uncrouch earlier to avoid slowing down.

If you are **NOT** attempting a crouch boost, still try to avoid steep slopes for similar reasons as with zero speed badge, as they may be *slightly* slower without them. Shallow slopes are still great to run down, however.

#### Fast Dash (Slope Boosts)

Mechnically, Fast Dash and no speed badge work very similar in this discussion. Short or steep slopes are typically bad, while shallow slopes are the way to go.

However, Fast Dash users are able to utilize another *functionally* exclusive trick known as **slope boosts**.

A slope boost is very similar to a [fast acceleration](https://notcodek.github.io/TestProjectWonderTut/fast_accels) except it is done on a short steep slope to give a slight speed boost.

You can watch this video explanation by *Smudey* for more details.

<iframe
  width="560"
  height="315"
  src="https://www.youtube.com/embed/MPgHkxWqQq8?start=365"
  title="Slope Boosts"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>

(Technically, slope boosts *do* work without a speed badge, however they are much less powerful, which is why they are explained in this section)

## TL;DR

General:
- Avoid running uphill, **always jump over upward slopes**
- Sliding down slopes is ***NOT*** faster, unlike other recent 2D Mario games

Badge-specific:
- No Speed Badge: **Avoid/jump over** short (1x1, 2x1) or steep slopes (2x2, 3x3, etc.), **run down** shallow slopes.
- Jet Run: **Run down all slopes**, and optionally attempt a "**Crouch Boost**" by pressing crouch the frame after you touch flat ground after the slope.
- Fast Dash: Same as Badgeless, except for short slopes you can attempt a "**Slope Accel**" to gain additional speed. (For more info, watch video above)
