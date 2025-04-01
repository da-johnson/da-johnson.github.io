---
title: "Octanol Assisted Liposome Assembly"
date: 2016-04-27
toc: false
type: project
---
<script type="module" src="https://ajax.googleapis.com/ajax/libs/model-viewer/4.0.0/model-viewer.min.js"></script>

<div class="article-container pt-3">
    <h1>How Microfluidics are Changing Synthetic Biology</h1>
  
    <div class="article-metadata">
      <span class="article-date">Apr 27, 2016</span>
    </div>
  
    <div class="btn-links mb-3">
      <a class="btn btn-outline-primary btn-page-header" href="/slides/example/" target="_blank">
        Slides
      </a>
      <a class="btn btn-outline-primary btn-page-header" href="https://twitter.com/georgecushen" target="_blank" rel="noopener">
        <i class="fab fa-twitter mr-1"></i>Follow
      </a>
    </div>
  </div>
  
  <div class="article-header article-container featured-image-wrapper mt-4 mb-4" style="max-width: 1080px; max-height: 720px;">
    <div style="position: relative">
      <img src="/project/example/20250314.png" width="720" height="405" alt="" class="featured-image">
      <span class="article-header-caption">Model Render via Blender</span>
    </div>
  </div>
  
  <div class="article-container">
    <div class="article-style"> 
      <p>I first became interested in lipid membranes during my early undergraduate studies of protein structure. One can only avoid exploring membranes for so long as a structural biologist, given the many membrane-associated proteins nature has provided. The capabilities unleashed by pairing proteins with a membrane become immediately apparent when exploring energy related systems such as proteorhodopsin, ATP-synthase, etc. where proteins provide a force to push protons across an impermeable membrane and generate a proton gradient with tremendous potential. Complimentary to this of course are the proteins which take advantage of this battery of potential energy to carry out actions in the cell such as the flagellar motor, a protein-based engine which turns proton flow into propulsive force by spinning the flagellum at the speed of a jet engine.</p>
  
      <p>For the purposes of my project, I was interested an additional capability afforded by membranes, that as the anchor phase for surface display proteins. In a natural cell, it is not uncommon to count greater than 50% of the molecules in a membrane to be proteins. The surface of cells are densely packed with receptors, pores, transporters, and adhesins. When I first began designing small molecule detectors, I turned to natural receptors which provide a signal to the inside of the cell notifying it of external chemical changes. Naturally, these systems represent the capabilities I would like in a sensor, that of high specificity, robust to a variety of environmental aggressors, and easily produced naturally. Additionally, I wanted to pattern my sensors in an array which would allow me to control their ratio and localization, as well as attach them to surfaces where they could remain immobilized.</p>
  
      <p>Giant unilamellar vesicles (GUVs) resemble the cell membrane of natural cells, particularly the lipid components, although they lack the myriad complex elements found in natural cell membranes, such as the diverse array of membrane-associated proteins that can constitute over 50% of the membrane's makeup. GUVs are primarily used by researchers focused on lipid systems and are invaluable for studying the diffusion of substances across these systems.</p>
      
      <p>Several methods are employed to produce GUVs, each with its own advantages and limitations:</p>
      <ul>
        <li><strong>Thin Film Hydration and Extrusion:</strong> This method involves drying lipids to form a thin film on a surface. The desired internal contents are then applied to this film and agitated to encourage the formation of vesicles...</li>
        <li><strong>Inverted Emulsion:</strong> In this method, lipids are mixed with a carrier oil to keep them solvated before vesicle formation...</li>
        <li><strong>Microfluidic Production of GUVs:</strong> Microfluidics involve devices with micron-scale liquid channels and are used in various research settings due to their low volume requirements...</li>
      </ul>
    </div>
  
    <model-viewer id="animation-demo" autoplay ar ar-modes="webxr" scale="0.1 0.1 0.1" camera-orbit="0deg auto auto" shadow-intensity="1" camera-controls touch-action="pan-y" src="20250317.glb" alt="A 3D model of a horse galloping.">
      <div slot="hotspot-nose" class="anchor"></div>
      <div slot="hotspot-hoof" class="anchor"></div>
      <div slot="hotspot-tail" class="anchor"></div>
      <div slot="hotspot-lipid" class="anchor"></div>
      <div slot="hotspot-outer" class="anchor"></div>
    </model-viewer>
  
    <video width="100%" height="100%" controls autoplay loop muted playsinline>
      <source src="20250317.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
  
    <video width="100%" height="100%" controls autoplay loop muted playsinline>
      <source src="emulsion.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
  
    <div class="article-tags">
      <a class="badge badge-light" href="/tag/deep-learning/">Deep Learning</a>
    </div>
  
  </div>
  