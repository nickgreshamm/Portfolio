---
title: "Flow Battery Development"
date: 2024-08-27T20:45:13+10:00
draft: true
author:
tags:
image:
description:
toc:
---

Redox flow batteries differ from conventional batteries in their use of aqueous electrolytes, allowing them to separate power storage from power output. This makes them ideal for deployable, static energy storage. During operation, electrolytes flow from tanks into power modules were the energy conversion takes place. For my thesis, I designed a novel method of assessing battery performance using computational fluid dynamics (CFD). My work also included a revolutionary improvement of the mechanical design for assembly which reduced the part number of a single cell from five pieces which were manually assembly, to a single, more robust piece, assembled in a single step using an over mould injection process.

## Solution

The final 3D model of the full flow stack is shown below, with the first 3D printed prototype (bottom left) and injection over mould die of the final design (bottom right).

![Full flow stack 3D model](/images/projects/3d-model.png)
![Manufacturing process](/images/projects/manufacture.png)


## Process

Iron flow batteries store and produce energy by leveraging the energy transition required to transition iron between its three available redox states. During operation element iron is deposited at the negative electrode. This process heavily influences many flow characteristics throughout operation.Therefore, the efficiency of iron flow batteries hinges on the deposition of iron at the negative electrode, for a more uniform deposition of iron, a more uniform flow is required. My hypothesis for the thesis was that by manipulating flow rate and flow topology the uniformity of the flow could be improved. 

### Computational Fluid Dynamics

To my knowledge, no study has been conducted which accesses the efficiency of flow batteries using computational fluid dynamics. This meant I had to determine my own metric by which to measure it. I used ANSYS fluent to simulate the required flow conditions of each topology. I then extracted the local velocity data for 1000 points through the centre of the electrode and calculated an average ±10% and 15% error bars around the average velocity. By calculating the number of the data points which fell within this range, I determined the flow uniformity of that particular flow topology. The images below show how my iterative design manipulations resulted in the increase in flow uniformity from 3.9-6.2% to 67.3-83.6%.

![CFD simulation 1](/images/projects/testing1.png)
![CFD simulation 2](/images/projects/testing2.png)

### Improvement to mechanical design and 3D Printed Prototype

The original design used 5 pieces to construct a single cell. These parts were the positive and negative flow paths, the electrode, and 2 gaskets for each side of the assembly. Through collaboration with industry partners at AMEC Plastics – injection moulding specialists - a novel design was created in which both the positive and negative flow paths would be injected simultaneously, in an over mould that would encase the electrode. This change in manufacturing and assembly method reduced the assembly time from approximately 6 minutes to 8 seconds.

## Project Summary and Professional Development

My work at ESIAP significantly advanced my engineering skills. It challenged me to apply theoretical knowledge to real-world problems, enhancing my abilities in CFD, advanced manufacturing, and interdisciplinary collaboration. The project's success in improving flow uniformity and streamlining manufacturing demonstrates my capacity for innovation in renewable energy. Working with industry partners also improved my communication and project management skills, preparing me for future challenges in sustainable energy solutions.

## Relevant Links
[1. ESI commissions the first Iron Flow Battery in Australia at the National Battery Testing Centre](https://press.esiap.com.au/releases/2023-1-24-esi-commissions-the-first-iron-flow-battery-in-australia-at-the-national-battery-testing-centrenbsp)

[2. ESI welcomes Stanwell Corporation Limited to visit the first Australian commissioned Iron Flow Battery](https://press.esiap.com.au/releases/2023-1-24-esi-welcomes-stanwell-corporation-limited-to-visit-the-first-australian-commissioned-iron-flow-batterynbsp)



