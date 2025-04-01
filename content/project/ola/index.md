---
title: 'Octanol Assisted Liposome Assembly'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
- block: markdown
content:
    title: 'My Research'
    subtitle: ''
    text: |-

- block: markdown
content:
    title: 'model-viewer'
    subtitle: ''
    text: |-

        {{<model-viewer src="1.glb" ar ar-modes="webxr scene-viewer quick-look" camera-controls tone-mapping="neutral" poster="poster.webp" shadow-intensity="1">
            <div class="progress-bar hide" slot="progress-bar">
                <div class="update-bar"></div>
            </div>
            <button slot="ar-button" id="ar-button">
                View in your space
            </button>
            <div id="ar-prompt">
                <img src="https://modelviewer.dev/shared-assets/icons/hand.png">
            </div>
        </model-viewer>}}
---