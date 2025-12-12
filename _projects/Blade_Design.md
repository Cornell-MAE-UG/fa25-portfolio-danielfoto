---
layout: project
title: Wind Turbine Blade Design
description: Small-scale wind turbine blade optimized for aerodynamic performance and structural reliability
technologies: [Fusion 360, Engineering Design, Fluid Dynamics]
image: /assets/images/twist.png
---


# Project Overview
This project focused on designing three blades for a small-scale wind turbine that maximize power extraction while preventing structural failure. The work integrated several core engineering areas:  
- **Materials & Mechanics** to ensure structural integrity under loading  
- **Fluid Dynamics** to analyze airfoil behavior and aerodynamic efficiency  
- **Engineering Design Principles** to optimize overall performance within real-world constraints  

# Design Process

The design process began with researching airfoils suitable for small‑scale wind turbines. We selected the NACA 4412 due to its strong performance at the low Reynolds numbers expected in our wind‑tunnel setup. Using a representative wind speed of 6.5 m/s, a hub chord of 1.2 in , and a kinematic viscosity of 1.5 x 10^(-5), we estimated a Reynolds number on the order of 10^4, confirming that a cambered, high‑lift airfoil like the 4412 was appropriate.


We maximized the allowable blade length and selected a 6‑inch radius to increase torque. For chord distribution, we adopted a tapered profile to account for the increasing relative velocity from root to tip. A geometric constraint limited the maximum chord to under 2 in, leading us to choose a 1.2‑in root chord (≈20% of the radius) for structural strength and a 0.4‑in tip chord to reduce drag.


The most challenging parameter was blade twist. While literature suggested 10–20°, our initial 15° twist was distributed too uniformly due to evenly spaced airfoil sections, resulting in a nearly straight blade. We revised the design to a total twist of 25°, increasing pitch from 2° at the root to 27° at the tip. In retrospect, concentrating more twist near the root and tapering it toward the mid‑span and tip would have produced a more realistic and aerodynamically efficient distribution.

# Testing Summary
The blades were tested by first identifying the wind‑tunnel frequency at which they began to rotate. At that speed, we applied an initial current to the torque brake and increased it in 0.2‑V increments until the blades stalled, recording the corresponding values. We then reset the torque‑brake voltage to its baseline and repeated the procedure at progressively higher wind‑tunnel frequencies. This process continued until the blade rotation approached the 2000‑RPM limit.
To analyze performance, we collected power curves across a range of wind‑tunnel frequencies and superimposed them on a single graph for comparison. From these curves, we identified the rotational speed at which the turbine achieved maximum power output.

# Contribution
I was responsible for creating the CAD model of the wind‑turbine blade. This required researching, alongside my team of three individuals, the key design parameters that influence performance such as blade twist, chord length, overall blade length, and the choice of airfoil cross‑section. I also ensured that all dimensions met the project constraints, including the attachment interface needed to securely mount the blades in the wind tunnel.

# Figures

<table align="center">
  <tr>
    <td align="center" style="padding: 15px;">
      <img src="/assets/images/model.png" width="100"/><br/>
      <em>Figure 1: CAD Model</em>
    </td>

    <td align="center" style="padding: 15px;">
      <img src="/assets/images/setup.png" width="250"/><br/>
      <em>Figure 2: Wind Turbine Blades in the Setup</em>
    </td>

    <td align="center" style="padding: 15px;">
      <img src="/assets/images/curve.png" width="250"/><br/>
      <em>Figure 3: Power vs RPM Curves</em>
    </td>
  </tr>
</table>


