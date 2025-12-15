---
title: Skatescape
description: Side-scrolling rythm game with a neon-futuristic pixel artstyle.
date: 2024-12-01 12:00:00 +0200
categories: [Game, Unity (Game), Unity (Editor)]
tags: [unity, programming]
portfolio: true
image:
  path: /assets/img/portfolio/key/skate_gameplay.webp
  lqip: /assets/img/portfolio/key/skate_gameplay_lqip.webp
  alt: Skatescape gameplay.
---

Release year: <span class="highlighted">2024</span>
{: .font-med }

Platform: <i class="fa-solid fa-globe"></i> <span class="highlighted">Web</span>
{: .font-med }

Engine: <i class="fa-brands fa-unity"></i> <span class="highlighted">Unity</span>
{: .font-med }

---

## My responsibilities

<i class="fa-solid fa-code" style="color:#2ddf2d;"></i> Lead Game Programmer<br>
<i class="fa-solid fa-screwdriver-wrench" style="color:#4c8cce;"></i> Tools Programmer<br>
<i class="fa-solid fa-bug" style="color:#df3e2d;"></i> Debugging

---

## Project

Skatescape is a rythm game inspired by Vib-Ribbon where you need to dodge obstacles by performing actions and combos.

Most of my time for this project went into programming tools for my team to create beatmaps and play frame based animations.
I was responsible for creating all the core game mechanics for the player and obstacles.

![Gameplay](/assets/img/portfolio/skatescape/skate_gameplay.gif)

### Key features

- Stage based gameplay with highscores and combo counters
- Obstacles synchronized to music
- Player combo actions

### Beat Editor

The project required some way to create accurate mappings of obstacles to audio so I created a tool that extends Unity's timeline tool to create a beatmap editor.

Since the timeline package offered accurate editing of nodes on a timeline with time steps it made it very easy to create an extension where nodes on the timeline are obstacles.
Timeline also offered a track for audio which displays the audio in a spectrum that helps with aligning the beat nodes.

The timeline assets are then parsed to binary which can be played back in the game.

![Beat Editor](/assets/img/portfolio/skatescape/beateditor.webp)

### Frame Animator

Frame based 2D animation tool for animating sprites the traditional way which solves plethora of issues with Unity's Animator for 2D animation.

**Features**
- FrameAnimation assets that can be used to create sprite animations
- FrameAnimator component that handles playing animations with it's internal clock
- No reliance on state machines or transitions
- Ease of swapping animations instantly by swapping FrameAnimation assets on the FrameAnimator component
- Removes frame timing jitter by optionally waiting for a frame to finish playing before swapping it to a new one
- Starting animation from a specified frame instead of start of the animation

![Frame Animator Inspector](/assets/img/portfolio/skatescape/frameanimator_inspector.gif)
*FrameAnimation asset inspector.*

![Frame Animator Create Shortcut](/assets/img/portfolio/skatescape/frameanimator_create.gif)
*Shortcut for creating a frame animation from spritesheet.*

## Try it out

<iframe frameborder="0" src="https://itch.io/embed/3158018?border_width=2&amp;bg_color=1b1b1e&amp;fg_color=eeeeee&amp;link_color=f69547&amp;border_color=363636" width="554" height="169"><a href="https://lasriel.itch.io/skatescape">Skatescape by Lasriel, Frass, Skunbylgo, ou6h, PumpunPoju, Kageroomaru</a></iframe>