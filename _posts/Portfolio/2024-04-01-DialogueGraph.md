---
title: Dialogue Graph
description: Node-based dialogue editor for Unity using the experiemental GraphView API.
date: 2024-04-01 12:00:00 +0200
categories: [Tool, Unity (Editor)]
tags: [unity, programming, editor]
portfolio: true
image:
  path: /assets/img/portfolio/key/dialogue-graph.webp
  lqip: /assets/img/portfolio/key/dialogue-graph_lqip.webp
  alt: Dialogue graph editor window.
---

Creation year: <span class="highlighted">2024</span>
{: .font-med }

Programming language: <span class="highlighted">C#</span>
{: .font-med }

Engine: <i class="fa-brands fa-unity"></i> <span class="highlighted">Unity</span>
{: .font-med }

---

## Project

I started this project during 2022 and finished most of the core features but the project went on a hiatus until 2024 where I started a project that required a dialogue system. During that project I polished most of the issues and improved some of the older systems.

This tool was made on the old GraphView API which is going to get replaced by [Graph Toolkit](https://docs.unity3d.com/Packages/com.unity.graphtoolkit@0.4/manual/introduction.html){:target="_blank"} package.

### Dialogue Graph

Dialogue graph is node-based dialogue editor made using Unity's experimental GraphView API which allows quick and easy way to create complex scenarios with branching dialogue in an intuitive way.

#### Key features

- Ability to create branching dialogue using choices and flags
- Creating, saving and loading graph assets, runtime data is saved separately
- Blackboard for managing graph data
- Minimap for navigating large graphs
- Node groups
- Event triggers

---

#### Nodes

##### Entry node

Index based entry point for the dialogue.

![Entry node](/assets/img/portfolio/dialogue-graph/node-entry.webp)

##### Dialogue nodes

Single choice dialogue node is used for showing dialogue to the player while multiple choice dialogue node presents player multiple choices and branches out depending on the choice made.

![Dialogue node](/assets/img/portfolio/dialogue-graph/node-dialogue.webp)

##### Flag nodes

Flag nodes can be used to set or unset flags and check whether a flag is set or not and branch out depending on the outcome.

![Flag nodes](/assets/img/portfolio/dialogue-graph/node-flag.webp)

##### Event node

Event nodes trigger an event which listeners can react to during runtime.

![Event node](/assets/img/portfolio/dialogue-graph/node-event.webp)

#### Blackboard

Blackboard is used to store data on which characters are included in the graph and interpolation data which is used to replace tags with variables like how many times the player has died.

![Blackboard](/assets/img/portfolio/dialogue-graph/blackboard.webp)

### Characters

Dialogue graph uses character assets to specify information about the current "actor" that is talking. They can include information like name, portrait or text color.

![Character inspector](/assets/img/portfolio/dialogue-graph/character-inspector.webp)
