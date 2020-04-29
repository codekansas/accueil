---
layout: post
title: 3D Printed Dishwasher Chopstick Catcher
author: Ben
---

Inspired by a really cool project on [/r/functionalprint][prev-post], I wanted to print a plastic piece that would fit into the dishwasher utensil tray and prevent chopsticks from falling through the bottom. After the bulbasaur planter, this was our first functional 3D print. It seemed like an ideal project - it was pretty specific to our dishwasher and unlikely to be something that we could buy online, and it wasn't too big so it wouldn't take too much time or filament to print.

The first step was to figure out the right dimensions of the tray. There were a few ways we tried. First, we tried taking a pink sticky note and tracing around the bottom of the tray. This worked pretty well, but it didn't feel enough like what an actual engineer would do, so afterwards we took calipers to the tray to double check our measurements.

![Initial design](/public/pics/2020-04-15-dishwasher-chopstick-catcher/dishwasher-drawing.png)

I spent about half and hour designing the piece in OpenSCAD while we were watching a movie called Okja with Chi's sister. It ended up being a pretty fun challenge to add the slots in the right way - we ended up having to be a bit clever with the `offset` function. For such a seemingly complex piece, it didn't end up taking very much code at all.

{% gist 2905a5d9abf80d1ad1a70362dfeff8b6 %}

Here's the final STL. It is pretty specific to our dishwasher tray, but the general idea is probably relevant to most dishwashers (this has been a thorn in my side for years).

<iframe id="vs_iframe" src="https://www.viewstl.com/?embedded&url=http%3A%2F%2Fle.bolte.page%2Fpublic%2Fstls%2Fdishwasher.stl"></iframe>

We also had to find a printer filament that would be dishwasher safe. Regular PLA wouldn't work, and ABS, which is what most people use for this kind of stuff, was smelled really bad (we're stuck inside because of the coronavirus outbreak, and opening the window didn't cut it). Plus, our 3D printer had trouble getting hot enough to melt ABS reliably, and even when it did, it got everywhere and was a pain to get working.

However, not to worry! Chi's sister's boyfriend Marc recommended using [nGen Colorfabb][ngen-colorfabb] filament, which was fantastic. On the first print, I got greedy and tried to remove the print before the tray had finished cooling down, which ended up shattering the piece. Lesson learned: the cooling process is important, because when the plastic cools down, the contraction pulls it back from the glass surface.

And here it is, the final product in action!

![Catcher](/public/pics/2020-04-15-dishwasher-chopstick-catcher/catcher.png)

Honestly game changing. Better living through technology.

[prev-post]: https://www.reddit.com/r/functionalprint/comments/cdnkt8/dishwasher_basket_for_straws_chopsticks/
[ngen-colorfabb]: https://ngen.colorfabb.com/
