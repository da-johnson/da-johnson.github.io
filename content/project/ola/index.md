---
title: 'How Microfluidics are Changing Synthetic Biology'
date: 2024-05-19
type: page
---
I first became interested in lipid membranes during my early undergraduate studies of protein structure. One can only avoid exploring membranes for so long as a structural biologist, given the many membrane-associated proteins nature has provided. The capabilities unleashed by pairing proteins with a membrane become immediately apparent when exploring energy-related systems such as proteorhodopsin, ATP-synthase, etc., where proteins provide a force to push protons across an impermeable membrane and generate a proton gradient with tremendous potential. Complimentary to this of course are the proteins which take advantage of this battery of potential energy to carry out actions in the cell such as the flagellar motor, a protein-based engine which turns proton flow into propulsive force by spinning the flagellum at the speed of a jet engine.

For the purposes of my project, I was interested in an additional capability afforded by membranes: that as the anchor phase for surface display proteins. In a natural cell, it is not uncommon to count greater than 50% of the molecules in a membrane to be proteins. The surface of cells is densely packed with receptors, pores, transporters, and adhesins. When I first began designing small molecule detectors, I turned to natural receptors which provide a signal to the inside of the cell notifying it of external chemical changes. Naturally, these systems represent the capabilities I would like in a sensor—high specificity, robustness to a variety of environmental aggressors, and natural production. Additionally, I wanted to pattern my sensors in an array which would allow me to control their ratio and localization, as well as attach them to surfaces where they could remain immobilized.

Giant unilamellar vesicles (GUVs) resemble the cell membrane of natural cells, particularly the lipid components, although they lack the myriad complex elements found in natural cell membranes, such as the diverse array of membrane-associated proteins that can constitute over 50% of the membrane's makeup. GUVs are primarily used by researchers focused on lipid systems and are invaluable for studying the diffusion of substances across these systems.

Several methods are employed to produce GUVs, each with its own advantages and limitations:

- **Thin Film Hydration and Extrusion:**  
  This method involves drying lipids to form a thin film on a surface. The desired internal contents are then applied to this film and agitated to encourage the formation of vesicles, which encapsulate the solution as the lipid film swells. Often, these vesicles are irregular in shape and size and require size extrusion, typically done using a syringe extruder. Here, GUVs are loaded into a syringe and pushed through an etched extruder disk, which shears and reseals them as they pass through a predetermined pore size. Multiple passes through the pores in alternating directions ensure uniformity in size, with the final pass collecting the finished vesicles in the receiving syringe while discarding any unextruded vesicles.

- **Inverted Emulsion:**  
  In this method, lipids are mixed with a carrier oil to keep them solvated before vesicle formation. The desired internal solution is vigorously mixed with the oil-solvated lipids to create an emulsion. As this emulsion settles, the lipids begin to assemble into micelles. This mixture is then introduced to a solution that will form the external environment of the GUVs. The denser micelles may sink to the bottom, potentially crossing the oil-water boundary, particularly if centrifugal force is applied to hasten this process. As they cross the boundary, a bilayer forms with the lipid heads orienting outward towards the aqueous solution.

- **Microfluidic Production of GUVs:**  
  Microfluidics involve devices with micron-scale liquid channels and are used in various research settings due to their low volume requirements, reducing both risk and cost. In the context of GUVs, microfluidic systems typically have three inputs and one output to mix the inner solution, lipid-in-oil, and outer solution precisely, facilitating the assembly of GUVs. Below, the operation of such chips and the detailed assembly process are further explored.

## View My 3D Model
{{< modelviewer >}}
{{< OLA-video >}}


