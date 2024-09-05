---
title: Infinikin
emoji: " "
date: 2024-09-05T05:18:25.651Z
summary: Monster battler with generated monsters
metaDescription: This is a sample meta description. If one is not present in
  your page/project's front matter, the default metadata.desciption will be used
  instead.
tags:
  - javascript
  - node
---
##### A run-based monster battling randomizer

![Screenshot from Infinikin, an in-development monster battling game](/src/assets/img/infinikinscreen.jpg)

Infinikin is a monster battler with attacks that permanently run out. Each playthrough generates a new pool of monsters, and roguelike-inspired mechanics give players options to make meta-progress across multiple runs. Full development began in June 2022 and is ongoing.

* I﻿ created the "BattleBoard" system for running turn-based battles. This is inspired by the Blackboard pattern and enables easy implementation of complex, interacting battle effects as well as easy unit testing.
* I've used Unity's Universal Render Pipeline to achieve textured outline effects on the monsters and environments, as well as to learn more shader techniques.
* M﻿y monster generator combines static body part assets and texture operations to construct new monsters, using metadata tags to select names, parts, and colors to match each monster's type and role.