---
sort: 1 
---

# Introduction
## Overview
We developed a microfluidics-based system for the analysis of C. elegans locomotory behavior in response to defined spatial and temporal stimulus patterns. We designed 2 x 2 cm structured arenas with regulated fluid flow that allow C. elegans to perform crawling-like locomotion resembling normal behavior on agar surfaces. Stimuli are delivered in the fluid phase and odor-evoked behaviors in the arena are automatically captured, segmented and analyzed using the MATLAB scripts available here. 

## [Publication](https://wp.wpi.edu/qntl/research-2/publications-2/)
Albrecht, D.R. & Bargmann, C.I. High-content behavioral analysis of Caenorhabditis elegans in precise spatiotemporal chemical environments. Nature Methods (2011), [doi:10.1038/nmeth.1630](https://doi.org/10.1038/nmeth.1630)

## Photomask Design
A photomask file suitable for fabricating 22 mm arenas presenting chemical pulses, stripes, and gradients is available in Postscript (.eps) format. This file replaces Supplementary File 1 in the publication, which was slightly altered upon conversion. 

```caution
Please note that no AutoCAD (.dwg) version is currently available due to curve complexity. However, most print shops can produce photomasks from .eps formats. 
```

## MATLAB Tracking and Analysis scripts:
MATLAB scripts (m-files) accomplish the following basic tasks:

 * ArenaTracker: Segment video file (.AVI) to obtain worm tracks. Code adapted from the parallel worm tracker.
 * SegmentTracks: Identifies instantaneous behavioral states from worm tracks and morphological data.
 * Ethogram: Displays ethogram and summarizes behavioral state probability and speed over time.
 * WormDensity: Summarizes behavioral state and speed data over space and time.

Video tracking, behavior segmentation, and data analysis were performed using MATLAB R2016+ with the Image Processing toolbox. Scripts have been tested on Windows 10. 

## Example Video 
C. elegans in a microfluidic behavior arena, captured with a [single worm tracker](http://www.mrc-lmb.cam.ac.uk/wormtracker/).

<div class="embed-container">
  <iframe
      src="https://player.vimeo.com/video/21194888/"
      width="500"
      height="281"
      frameborder="0"
      webkitallowfullscreen
      mozallowfullscreen
      allowfullscreen>
  </iframe>
</div>

