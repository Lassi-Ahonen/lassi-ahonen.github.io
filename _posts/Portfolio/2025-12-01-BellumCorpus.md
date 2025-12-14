---
title: Bellum Corpus
description: Prototype turn-based strategy game where you control mutated human weapons in their quest for destruction.
date: 2025-12-01 12:00:00 +0200
categories: [Game, Unity (Game), Prototype]
tags: [unity, programming, graphics, editor, prototype]
portfolio: true
image:
  path: /assets/img/portfolio/key/bellumcorpus_gameplay.webp
  lqip: /assets/img/portfolio/key/bellumcorpus_gameplay_lqip.webp
  alt: Bellum Corpus gameplay.
---

Creation year: <span class="highlighted">2025</span>
{: .font-med }

Platform: <i class="fa-brands fa-windows"></i> <span class="highlighted">Windows</span>
{: .font-med }

Engine: <i class="fa-brands fa-unity"></i> <span class="highlighted">Unity</span>
{: .font-med }

---

## My responsibilities

<i class="fa-solid fa-code" style="color:#2ddf2d;"></i> Lead Programmer<br>
<i class="fa-solid fa-screwdriver-wrench" style="color:#4c8cce;"></i> Tools Programmer<br>
<i class="fa-solid fa-cube" style="color:#8857d0;"></i> Technical Artist

---

## Project

Bellum Corpus is a prototype turn-based strategy game where player controls mutated human weapons against their old allies.

The project is built on Unity's High Definition Render Pipeline (HDRP).

During this project I was mainly responsible for:
- Developing and maintaining tools & shaders to create hex terrains and grids
- Developing a versitile and flexible binary format for saving data
- Leading the code direction and structure
- Keeping the asset and code base organized

### Key features
- Hex terrain
- Hex grid based movement and actions
- Enemies with basic AI and personalities
- Cover mechanics using line of sight

### Hex map editor

Hex map editor is a runtime level editor for creating hex terrains.

#### Edit mode

In edit mode the terrain and it's data can be modified with various tools.

##### Tools

**Brush**

![Brush Size](/assets/img/portfolio/hex-editor/brush_size.webp)
*Adjustable brush size.*

![Brush Shape](/assets/img/portfolio/hex-editor/brush_shape.webp)
*Ring brush shape.*

![Elevation Brush](/assets/img/portfolio/hex-editor/elevation.webp)
*Modified elevation using the elevation field.*

![Terrain Type Brush](/assets/img/portfolio/hex-editor/terrain_type.webp)
*Painted terrain types.*

![Water Brush](/assets/img/portfolio/hex-editor/water.webp)
*Painted water at different elevations.*

![Flag Brush](/assets/img/portfolio/hex-editor/flags.webp)
*Flag brush mode. Red tiles are hexes where selected flag is not set and green ones have the flag set.*

**Eraser**

Eraser is basically the same as brush tool but instead it resets affected hexes back to default values.

#### Config

Config can be used to change generation settings of the terrain.

![Config Mode](/assets/img/portfolio/hex-editor/config_mode.webp)
*Config mode interface.*

![Config](/assets/img/portfolio/hex-editor/config.webp)
*All config options.*

#### New, saving, loading and building

Map projects can be created, saved and loaded. Loaded maps can be built which creates a map binary that can be used inside the game.

![New](/assets/img/portfolio/hex-editor/create_new.webp)
*Creating a new map project.*

![Loading](/assets/img/portfolio/hex-editor/loading.webp){: width="350" }
*Loading a map project.*


## Try it out

<iframe frameborder="0" src="https://itch.io/embed/4113887?border_width=2&amp;bg_color=1b1b1e&amp;fg_color=eeeeee&amp;link_color=5a0513&amp;border_color=363636" width="552" height="167"><a href="https://reponami.itch.io/bellum-corpus">Bellum Corpus by reponami, SadFrogzz, Abramide, Insomnian, Lasriel</a></iframe>