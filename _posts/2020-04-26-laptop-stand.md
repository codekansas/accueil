---
layout: post
title: 3D Printed Laptop Stand
author: Ben
---

*Preface: this isn't an actual stand, it is just a stand to hold a laptop upright so that it takes up less desk space. In my opinion this constitutes a real stand, but when he told his friend Matt about it Matt assumed it meant some kind of stand to elevate a laptop to eye level height, which it isn't. Although Chi wanted to print this, so we might do that in a future project.*

The Covid-19 induced quarantine has hit the world hard, but perhaps none have been hit harder than the tech worker. Indeed, these creatures have hitherto known nothing but a life of free food, snacks, massages and standing desks. Yes, while many across the country are struggling though such trivialities as the deaths and sicknesses of loved ones or crippling job loss and unemployment, these tech workers have had to deal with the horrors of having to cook food for themselves, and dealing with sometimes spotty wifi.

This is obviously sarcastic. Both Chi and I have been extremely fortunate to be able to stay safe inside together during this pandemic, without having to worry about losing our jobs. However, it has taken some time to get used to our new arrangement. Besides going from living in different timezones to spending 24 hours a day within the same 500 square foot studio apartment, it's been interesting to adjust to the challenges of working remotely. I bought a fancy new monitor and standing desk on Amazon, because otherwise I was going for whole days without even standing up. About two weeks into quarantine, my work laptop's `i` key started to get stuck, which makes a big difference as a programmer who is terrible at coming up with unique variable names, so I also bought a new keyboard and mouse (the laptop in question is one of the Macbooks with the really crummy butterfly keyboards - it is not the first laptop I've had which has had this problem 😕).

Tragically, however, the keyboard doesn't leave a whole lot of desk space. Enter the 3D printer. Inspired by the Nintendo Switch stand, I wanted something to store my laptop upright, so that I could just plug it into my monitor. There's this little 2FA USB fob thing on the side that I needed to keep available too. I got the laptop dimensions from Apple's website, and Chi and I whipped out OpenSCAD and went about designing the holder (as in one of our [previous posts][prev-post], a non-negligible amount of the designing process took place while watching a movie with Chi's sister, although in this case it was a zombie movie which we actually thought was terrifying).

The final design was actually quite a bit more complicated than I thought it would be. During college, Chi did a course on architecture of cathedrals and was adamant about including buttresses, hence the unfortunately-named `butwid` and `butfact` variables.

{% gist 75f3d8e1c1dd6aee6d30de147ebb364c %}

Here's the final STL, using the parameters from the above code. It's parameteric so if you want to make one yourself, you can mess with the variables at the top.

<iframe id="vs_iframe" src="https://www.viewstl.com/?embedded&url=http%3A%2F%2Fle.bolte.page%2Fpublic%2Fstls%2Flaptop.stl"></iframe>

We used the same [nGen Colorfabb][ngen-colorfabb] filament from the [dishwasher][prev-post] build. This might not have been such a good idea, since we didn't really need it to be dishwasher safe or anything, and the nGen filament seems to be a bit more prone to leaving strands behind and clumping up aroudn the main verticals than the PLA is (although this might have just been the design - we don't have enough experience printing stuff yet, I think).

Here it is in action. It actually turned out quite well, despite some rough edges at the top. I thought I might need to put in some foam padding or something, but the plastic seems to be soft enough that I'm not too worried about scratching my laptop or anything.

![Stand](/public/pics/2020-04-26-laptop-stand/stand.png)

Stay safe!

[prev-post]: {% post_url 2020-04-15-dishwasher-chopstick-catcher %}
[ngen-colorfabb]: https://ngen.colorfabb.com/
