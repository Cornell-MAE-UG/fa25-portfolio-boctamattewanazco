---
layout: project
title: "Torque Wrench Redesign"
image: assets/images/torque-wrench.jpg
date: 2025-12-10
---

## Overview
This project focused on designing and optimizing a torque wrench handle using Fusion 360 and ANSYS Mechanical. The goal was to satisfy strength, fatigue, and fracture requirements while also meeting a sensitivity target of **≥ 1.0 mV/V** using strain gauges.

## Design Modeling
The CAD model was created in Fusion 360 using the following key dimensions:

- Length: 14 in  
- Width: 0.5 in  
- Thickness: 0.6 in  
- Fillet: 0.05 in  
- Drive size: 3/8 in  

Screenshots were exported to document the geometry.

## Finite Element Analysis
ANSYS Mechanical was used to compute:

- Normal strain in the gauge direction  
- Maximum principal stress  
- Normal stress  
- Total deformation  
- Strain probe value for sensitivity  

The model applied a **600 in-lbf** torque, converted into a force at the handle end.

## Material Selection
The final design uses **Ti-10V-2Fe-3Al**, chosen for its high strength, fatigue resistance, fracture toughness, and low density relative to steel.

## Results Summary
- Sensitivity: ≥ 1.0 mV/V  
- Safety factor (yield): Passed  
- Safety factor (fatigue): Passed  
- Safety factor (fracture): Passed  

This project demonstrated the full workflow of modeling, meshing, running structural simulations, and validating engineering constraints.

