+++
title = "What comes after triangles?"
date = "2026-06-03T14:02:56+05:30"
author = "clodman84"
authorTwitter = "" #do not include @
cover = ""
coverCaption = ""
tags = ["Computer Graphics", "Programming", "Hardware Renderer"]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = false
hideComments = false
color = "orange" #color from the theme settings
+++

> *This tale grew in the telling, until it became a history of the Great War of the Ring and included many glimpses of the yet more ancient history that preceded it.*
> *-- J. R. R. Tolkein*

To make something wholly your own is to hunt down every spectre of what it could become; there is always 'one more thing'. Those who are masters of their craft know when to put the hammer down, sit back, and admire their handywork. 

Not me though… Now where did I leave my spanner?

{{< figure src="/images/howl.webp" position="center" style="border-radius: 8px; width: 75%; display: block; margin: auto;" >}}

# The Nameless Thing


> *"Far, far below the deepest delvings of the Dwarves, the world is gnawed by nameless things."*
> *-- Gandalf The White in The Two Towers*

I maintain an [application](https://github.com/clodman84/Updated-Newer-Fresher-Version-3) to help identify, print and distribute over 20,000 photographs annually. Over three years and two rewrites, the app has morphed into a patchwork Goliath of superfluous features. Every new need an addition to a house that was never meant to have stairs. While I was hammering away in the basement of my pet titan, mounting the railings for the newfangled Google Drive integration; I encountered this nameless thing, this unwelcome void, this ghastly abomination: **this** empty canvas. 

{{< figure src="/images/taunting_me.png" position="center" style="border-radius: 8px; width: 75%; display: block; margin: auto;">}}

I could find no sling large enough no shoot it down, no purpose brobdingnagian enough to feed its insatiable apatite. No table, no loading indicator, no preview could encircle this beast, some part of it always stayed empty. 

> *He said to the woman, “Did God really say, ‘You must not eat from any tree in the garden’?" -- Genesis 3:1*

I soon realised that I would have to resort to using deeper magic to tackle the leviathan. The first of my endeavors was a clone of the Dinosaur Game from Google Chrome. Soon the dinosaur had learnt to jump, dash, double jump and ground slam. But I remained dissatisfied. Thus, began my expedition through the hallowed caves of the internet in search for a suitable spell. Soon, I stumbled across a recreation of the snake game on the SDL3 examples and tutorial page. 

<iframe 
  src="/demos/snake/snake.html" 
  width="100%" 
  height="500px" 
  frameborder="0"
  scrolling="no"
  style="display:block;border:none;padding:0;margin:0;">
</iframe>

For the uninitiated SDL or Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL/Direct3D/Metal/Vulkan. It is used by video playback software, emulators, popular games…… and my app. It's honestly surprising that it took this long for me to shoehorn a game into my very serious, totally necessary and 100% thought out photo tagging and editing application. You see SDL is a middleman, , it acts as a compatibility layer between my application and all the different environments my app runs on. SDL3 also introduced a GPU API, which does the busywork of catering to the idiosyncrasies of differing hardware and platforms for me.
