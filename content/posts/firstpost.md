+++
date = '2025-07-23T19:31:45+05:30'
draft = false 
tags = ['Computer Graphics', 'Programming']
title = 'Computer Graphics'
cover = 'images/quake.png'
coverCaption = "Quake 1996"
ToC = false
+++

I like videogames and I'm overconfident, so naturally when a YouTube video of someone making Minecraft with various levels of "from scratch" shows up in my feed, I can't help but feel like I could probably do that.

Around 6 months ago, I finally decided that I should probably do it, and showcase an awful game that I will justify as being impressive purely because of how much time I wasted reinventing the wheel.

Turns out it's much harder than I thought. Primarily because the field of GPU programming in general is a mess with a ton of competing frameworks I'm too stupid and inexperienced to choose from right now.

Most resources for learning how to do this seem to either abruptly stop a few metres ahead of a 15 year old roblox dev's attention span, or pick up after a PhD in making physically based renders of a raccoon's eyeballs. There seems to be an acute deficiency of intermediate computer graphics. Not that I am an intermediate (yet), it's just that the little Dunning-Kruger shaped gremlin living in my cranium could beat up your dad.

This is around the time most people discover Ray Tracing in One Weekend. But soon after rendering the shiny spheres, I realised that the leap from rendering shapes that can be described with a single equation and rendering a kangaroo composed of multiple vertices, faces and materials would require a comically large trampoline. Sure, I could probably fosbury flop a hacky way to render them, but I quickly realised that there would be no videogame at the end of this road I ended up not taking.

So I decided the best way forward would be try and replicate the methods used by people before GPUs were widespread. Recreating DOOM was out of the question since it wouldn't be something impressive enough to warrant the look of mild amusement from my friends (or anyone in my vicinity of my laptop for that matter) that serves as the apotheosis of my life's screenplay.

After firing up the internet archive shaped DeLorean and perusing through the woefully dusty shelf of computer graphics, I came across the mummified corpse of software renderers. Where my triangles never need to be shoved through the unholy orifice of a graphics pipeline. Instead the renderer sees through a 1-D array shaped blinker that is vomited into the framebuffer of your display. To the computer, all its doing is changing values in a singular array that serves as a surrogate for your screen (to be fair its more like one of the 3 eggs in IVF, I'm not sure which one). The program never leaves the increasingly warm embrace of your computer's CPU.

I will be documenting the entire process of me learning how computer graphics works over here, among other things. Mostly because showing off to a few dozen people just wasn't cutting it anymore, and partly because I hope to fill the gap in computer graphics resources by regurgitating things I barely understand myself.

