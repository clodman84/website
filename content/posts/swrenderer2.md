+++
title = "My Tiny Renderer (2/?)"
date = "2025-07-28T23:41:11+05:30"
author = ""
authorTwitter = "" #do not include @
cover = ""
coverCaption = ""
tags = ["Computer Graphics", "Programming", "Software Renderer"]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = false
hideComments = false
color = "orange" 
draft = true
+++

I did everything mentioned in the last article 6 months ago. I got sidetracked by a lot of different projects (like writing a really simple "graphics"/UI library for ssd1306 OLED displays, among other things). Frankly, I have no idea what I intended to do after rendering Suzanne's wireframe. Now that I have to face my commitment issues and complete the damn thing, I am lost. You see, at this point in time, rendering into a TGA image isn't interesting me anymore. Like a situationship that's falling apart, I crave for something that's responsive, realtime and spontaneous, not some pre-computed facsimile of the program's RAM in the form of a 2 dimensional image.

This lead me down the path of one of the most convoluted avenues of application programming, opening a window. After stumbling around for about an hour, I narrowed my options to Sokol and Raylib, the latter includes a Minecraft clone in it's showcase, [which I think is hilarious](/posts/firstpost). Before we get ahead of ourselves, we've got to understand what both of these free and open source libraries do.
