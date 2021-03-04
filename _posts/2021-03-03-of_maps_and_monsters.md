---
title: Of Maps and Monsters
date: 2021-03-03 22:00 -05:00
categories: [GameDev, Godot]
tags: [games, godot]
---

I've made reasonably good progress in the past two days. I can now assign initial elevation to tectonic plates:

![Tectonic Plates](/assets/img/202103/plates.png)

Generate plate drift:

![Plate Drift](/assets/img/202103/drift.png)

And calculate the effect adjacent plates will have on the terrain:

![Terraini](/assets/img/202103/contours.png)

I've made a few blunders in the way my data is stored, however.  For instance, I'm currently saving the terrain effect on the edges of the graph.  As I started to implement the overall terrain elevation displacement, I realized that this should be put on the individual vertices instead, as it makes traversing the graph in a breadth-first manner much simpler. That's what I'll work on for the next day or two, assuming the current crisis at work (why does one always happen when I start a personal project?) dies down quickly.