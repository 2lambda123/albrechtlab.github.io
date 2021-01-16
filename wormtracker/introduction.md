---
sort: 1 
<!---
	This is a comment.  Edit the number after the string 'sort:' above to set the order of appearance of the files on the webpage
--->
---

# Introduction
## Overview
We developed a microfluidics-based system for the analysis of C. elegans locomotory behavior in response to defined spatial and temporal stimulus patterns. We designed 2 x 2 cm structured arenas with regulated fluid flow that allow C. elegans to perform crawling-like locomotion resembling normal behavior on agar surfaces. Stimuli are delivered in the fluid phase and odor-evoked behaviors in the arena are automatically captured, segmented and analyzed using the MATLAB scripts available here. 

## Publication
Albrecht, D.R. & Bargmann, C.I. High-content behavioral analysis of Caenorhabditis elegans in precise spatiotemporal chemical environments. Nature Methods (2011), doi:10.1038/nmeth.1630

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

Video tracking, behavior segmentation, and data analysis were performed using MATLAB v7.0.1 with the Image Processing toolbox. Scripts have been tested on Windows XP and 7. 

## Example Video (Click the photo)
[![Single worm in microfluidic arena.](https://i.vimeocdn.com/video/136180805.jpg?mw=900&mh=675&q=70)](https://player.vimeo.com/video/21194888/ "Single Worm in microfluidic arena")




