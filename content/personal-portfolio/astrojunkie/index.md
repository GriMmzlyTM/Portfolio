---
title: "Astrojunkies"
date: 2022-01-14
draft: false
description: ""
summary: "Mobile bullet-hell rhythm game where enemies spawn and attack to your music"
tags: ["Personal", "Unity", "Mobile", "BulletHell"]
type: "personal"
---

{{<lead>}} Pew pew to some music {{</lead>}}

# The Project
{{<youtubeLite id="mAHjG70WGqI " label="Astrojunkies demo">}}

Astrojunkies is a 2D mobile bullet hell rhythm game I developed in 2018. 
The idea behind the project was to allow players to generate levels using their own music through Youtube or an MP3. 

This worked by analyzing the frequencies of the chosen song in real time and assigning different frequency ranges to specific buckets with the dB of said bucket being used to dictate potency of the action. 

For example, lets say that a hz range of 5K-9K summons a new enemy, the average dB of said range would dictate which tier of enemy is summoned. 

## Tools used  

**Game Engine**: Unity  
**VCS**: Git  

This was a very simple project, no external libraries were used.

## My part 

I was in charge of all programming for the project, my responsibilities included:
- Core gameplay loop (Game State)
- Entity management, pooling, and state
- Audio analysis and level generation
- Combat (Abilities, enemy projectile patterns, health)
- UI/UX programming
- Mobile performance optimization

## Learned experiences

This project was my first time working with audio, and boy was it a good learning experience! It took a bit of research to learn and understand how different frequencies could be loaded from an audio file to generate a "frequency map", as well as balancing this for different songs in a way that would feel dynamic and fun. 

Issues arose when trying to use different contrasting genres of music, such as Heavy Metal and Pop, or Country and Rap. The difficulty of the game would be drastically different, and enemies would not spawn or shoot correctly in songs that didn't have the proper frequency signatures.  
One solution for this was to use average frequency ranges that matched the largest variety of genres, along with relative dB ranged based on the song itself (I.E. detecting large changes in dB rather than set values)