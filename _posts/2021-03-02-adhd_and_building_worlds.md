---
title: ADHD and Building Worlds
date: 2021-03-01 22:40 -05:00
categories: [GameDev, Godot]
tags: [games, godot]
---

# ADHD and Building Worlds
Well, I  warned you.  As with all things personal project related, I lost interest/got busy at work/had too much to do at home/etc.  Now, four months later, I have a new project.
# Generative Worldbuilding
I've been an avid tabletop role-player since I was a kid. I've run my fair share of games, too, and when it comes down to it, one of my favorite parts of the hobby is creating new worlds. I love generating culture, technology/magic, species, historical events, plots, and points of interest.  One thing I've never enjoyed as much, however, is building the actual geography.  All of my worlds end up looking basically the same.  This is one reason I've been actively interested in procedural generation of game worlds for a long time.

One of the first really interesting takes I'd seen on the concept was from [this blog post](https://simblob.blogspot.com/2010/01/simple-map-generation.html) by Amit Patel, the developer of Realm of the Mad God.  His technique for generating islands was more controllable and natural-looking than the other methods I'd seen. I played around with it and had a basic island generator working in a few days, but I never made much use of it.

![Blob In Games Image](/assets/img/blobs-1.png) 

A few years later, Scott Turner started his [Here Dragons Abound](https://heredragonsabound.blogspot.com/) blog. I've wanted to recreate that methodology in a language I'm familiar with for years now.

![Here Dragons Abound Image](/assets/img/hda-1.png)

Then about a week and a half ago, some friends of mine introduced me to the game [Valheim](https://www.valheimgame.com/). Here is an open-world survivalcraft game with a lo-fi aesthetic that still manages to take advantage of modern graphics techniques, and uses (from the looks of it, at least) Simplex Noise to generate its archipelago-based worlds.

![Valheim Map](/assets/img/valheim-1.jpg)

Work has been mentally draining lately, so I needed something to renew and refresh my creative juices.  I spent a couple of evenings playing around in Godot, and came up with the basics of a plate tectonics system on a flat map, along with all of the graph data I'll need to apply some of Scott's concepts, along with a few things from Amit's later ProcJam entries.  I'm excited to program again!

![Early Tectonics](/assets/img/tectonics1.png)