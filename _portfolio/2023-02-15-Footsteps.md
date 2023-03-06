---
layout: post
title:  "Realistic spatial propagation for footsteps in Unity and Wwise"
date:   2023-02-15 00:42:06 +0200
categories: portfolio
logo_url: /assets/icons/unityinverse.jpg
---
The idea for this project was to create a more realisitc sounding propagation system for audio when inside a house. Rather than passing position and distance directly into wwise, I'm using Unity's AI navigation to determine how the sound propagates througho open spaces and influence different sound shaping parameters.

This was a project I'd been thinking about for a while. I got this inspiration after reading a blog post of the internal audio code team at Creative Assembly. 

The video below has a lengthy explanation using some 2D schematics as a approximation to explain the algorithm. 

<iframe width="680" height="385" src="https://www.youtube.com/embed/5rK5BsY53so" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>