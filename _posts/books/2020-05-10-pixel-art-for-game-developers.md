---
title: Pixel Art for Game Developers
image: /assets/img/game-dev
categories: books
---

## Pixel Art FTW

Pixel art was created due to technical restraints. However, players love pixel
pixel art due to nostalgia and the simplicity leads to memorable and iconic
imagery. Pixel art games use a highly accepted game styles. Each pixel conveys
as much information as possible which leads to iconic art where features are
exagerated.

> Pixel art looks intentional and timeless

For game developers, pixel art makes life easier. Sprites are literally pixel
sized resulting in tiny file sizes. They are somewhat easy to create and the
software needed to make them is cheap. It is easy to import into games and it
works well on small screens.

Compared to 3D, the design process is much simpler. Thus there are various
reasons to use pixel art in game development.

## Drawing Pixel Art

When drawing lines, focus on drawing straight lines or lines that follow a
consistent pattern. An important aspect of creating curves is to avoid lone
pixels as they break the ilusion of a curve. A line should always be 1 pixel
wide otherwise it turns aestheticly unpleasent.

> When importing pixel images, reduce/disable anti-aliasing. While on normal
> images/assets it can be useful to soften the image, for pixel art where every
> pixel counts it can easily turn our drawings blurry.

## The importance of Color

No pixel art would be what it is without a good color palette. While gradients
work with lots of colors it is much more common to have a ramp with fewer colors
as a palette. In fact, generating different sceneraries by changing just a few
color in our ramp is quite simple which makes this approach to coloring quite
powerful - **Palette swapping**. Using this technique we can quickly change the
same scenary into a sunset, night scene or dungeon scene while recycling
existing art and giving a differnt feeling. Beyond that, we can in the same
generate a special versions of characters like this as well for special attacks
or to reuse a character as a different version.

We can quickly see that the color palette is important. But what makes a good
color palette ? to begin with it should have as few colors as possible. While
more colors add more detail to our art, it also increases the drawing/animation
time **exponentially**. Too many colors also makes it dificult to keep our art
consistent.

How do we pick colors ? The easiest way is to generate a gradiend from dark to
light for each object we want to draw and keep that gradient as small as
possible. For a tree for example, we would pick 3 shades of green and 3 shades
of brown to add complexity to our tree. We could add an extra unrelated color
such as red to draw apples or black to draw a whole in the wood. Another
important part is saturation. A more saturated color draws the eye and makes it
stand out so use it wisely. Low saturation is generally good for backgrounds.

> This might be a lot to wrap our heads around but it boils down to keeping
> color palettes as simple as possible and using as little change as possible
> to make as much of an impact as possible.

A great way of learning about colors and coloring is to look at art drawn by
others.

## Tip and Tricks to draw better

> Most of what makes art look good has to do with shadowing, cast shadow, light
> consistency and linear perspective.

When it comes to shading, any surface that is perpendicular to the light,
reflects the most light and is thus the brightest part of the object. Any
surface that is parallel to the light source will appear darker. In a similar
way the shadow of our object should be aligned with the light source to create a
good feeling of depth. The shadow is darker closeer to the object and gets
lighter toward the edges. An extra tip at this point, a distant light source
casts a blurry shadow while a near light source (torch) casts a dark and rich
shadow.

Atmospheric Perspective is one way our brain determines the distance of objects.
Object appear smaller when they are far. If one object overlaps another, it
immedeatly converys a sense of depth. Returning to Atmospheric Perspective, very
distance objects (horizon, mountains, etc.) don't just appear smaller and
overlapped but lighter and bluish. Why ? because we are used to how the
atmosphere changes the color of things. For mountains this would mean the first
mountains are dark and become inreasingly lighter and bluer as they overlap
until they blend with the horizon.

The Linear Perspective is the guide we use to determine the size of objects to
give a feeling of depth. The lines start big and get smaller the closer they are
to the horizon.

If we combine all this concepts in our art we can create complex and rich
scenary with a lot of eye candy.
