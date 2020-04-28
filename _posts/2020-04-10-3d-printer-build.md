---
layout: post
title: Meet Jules - Our 3D Printer
---

# Phase 1: The Initial Build

After some time mulling over the idea of building our own 3D printer, Ben decided to get the [RepRap Prusa i3 Printer Kit](https://www.amazon.com/REPRAPGURU-Black-DIY-Prusa-Printer/dp/B01BO52LBA/ref=sr_1_3?crid=27CZF5UH06OUV&dchild=1&keywords=reprap%2B3d%2Bprinter%2Bkit&qid=1588096407&sprefix=rep%2Brap%2B3d%2Caps%2C167&sr=8-3&th=1). Apart from a digital electronics course in college during which we experimented with Arduino, Chi didn't have much experience with hardware. In contrast, Ben has built his own electric skateboard and tinkered with transcranial direct current stimulation. He even assembled his own 3-D printer once before in college even though it did not print as well as he has hoped. Nevertheless, starting from the initial unboxing of its many parts, it was evident that the assembly would be lengthy and honestly quite exciting. 

The initial build took us about 6 hours. While the instructions were easy to follow, we encountered a few challenges with our materials. Since the acrylic parts were not perfectly precise cut, Ben was able to shave some of the wedges to achieve a snug fit of the frame. Even though we did not have a screwdriver at Chi's apartment to secure the wires to the control board, we were able to find a fitted bobby pin and leveraged torque by grasping it with a needle driver (a surgical tool Chi uses to practice suturing on bananas). 

Once we reached the final step of the build manual, it was almost 10 PM, and we have finished assembling the physical backbone of our printer. However, our creativity could not fashion a voltmeter to adjust voltage of our stepper motor drivers. We took a pause, awaiting the arrival of our voltmeter.

# Phase 2: Electronics & Calibration

We approached the next 3-4 hours spent on figuring out the electronics part with optimism. From several failed attempts of adjusting the potentiometers, we realized that there must be a few non-functional stepper drivers among the 5 on the control board. After connecting the Arduino board to the laptop, we sequentially added the stepper drivers and identified the troublemakers as the computer failed to detect the board upon their presence. Since they are quite fragile, we got [replacement](https://www.amazon.com/BIQU-Compatible-Stepper-StepStick-Controller/dp/B01FFGAKK8/ref=sr_1_2?dchild=1&keywords=stepper+drivers&qid=1588106444&sr=8-2). 

With the abundance of wires, Ben also later organized and grouped the cords using [sleeves](https://www.amazon.com/100ft-Expandable-Braided-Sleeving-Sleeve/dp/B074GM1PK1/ref=sr_1_5?dchild=1&keywords=wire+sleeve&qid=1588103404&sr=8-5) and binder clips. We also used our trusty label maker to tag wires corresponding to 'X', 'Y', 'Z' axis. 

Once the electronics were operational, we initially used the suggested values provided in the build manual and then explored different parameters/features during calibration. From leveling the bed to ensuring clean extrusion, it was a process that required much patience.

# Phase 3: Meet Jules

**Say hi to Jules** 

Ben wanted to name our 3-D printer after one of his favorite authors [Jules Verne](https://en.wikipedia.org/wiki/Jules_Verne), who wrote _Around the World in Eighty Days_. On the other hand, Chi thought Jules would be a nice pun for joules (the unit of energy), which would allude to the ["ch'i" or "the vital force of living things"](https://en.wikipedia.org/wiki/Qi).

![Jules](/public/pics/jules.jpg)

# Our initial prints

Our first successful print was a small plaque using [glow in the dark PLA](https://www.amazon.com/NOVAMAKER-Filament-Dimensional-Accuracy-Luminous/dp/B0746FNJH6/ref=sr_1_5?dchild=1&keywords=pla+glow+in+the+dark&qid=1588108561&sr=8-5). Ben experimented with OpenSCAD and added our names to a rectangular base. We later attached it onto one of Jules' arylic frames as a momento of (hopefully) the beginning of our fun adventure in hardware. 

![Plaque](/public/pics/plaque.jpg)


Our first larger print was a [Bulbasaur planter](https://www.thingiverse.com/thing:381599) that we saw on Thingiverse, which hosts an extensive collection of others' STL files. One of our air plants that were generously gifted by Julia (Chi's sister) now found a wonderful home in a cute planter on Ben's desk.As we started to experiment with different filament, we also printed a second one using [Wood PLA](https://www.amazon.com/Filament-TECBEARS-Consumables-Dimensional-No-Tangle/dp/B08181LJLD/ref=sr_1_4?dchild=1&keywords=wood+pla&qid=1588109129&sr=8-4) for our second air plant. 

![bulbasaur](/public/pics/bulbasaur.jpg)

Check out some of our [newer prints][new-post]. 

[new-post]: {% post_url 2020-04-28-first %}
