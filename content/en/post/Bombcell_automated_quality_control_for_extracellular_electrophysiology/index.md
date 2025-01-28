---
title: 'Bombcell: automated quality control for extracellular electrophysiology'
date: 2025-01-09
authors: ['admin']
layout: post
categories: ['Human electrophysiology', 'Animal electrophysiology', 'Software']
tags: ['Human electrophysiology', 'Animal electrophysiology', 'Software']
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/@basal_gang
---
Recent advances in high-density neural probes, such as Neuropixels, have revolutionized electrophysiology. However, they produce large, complex datasets that require extensive quality control. This is typically done through  manual curation, which is time-consuming, subjective, and lacks standardization. 

We developed Bombcell (https://github.com/Julie-Fabre/bombcell) , an open-source, user-friendly toolbox that streamlines quality control for spike sorting outputs. Bombcell integrates five established and ten novel quality metrics, becoming the  first toolbox to  address the wide range of errors that can arise, including noise, non-somatic waveforms, multi-unit activity, and drift.

Bombcell employs a multi-step algorithm that first removes noise and non-somatic units based on waveform shape. It then divides units into time chunks to assess stability and remove periods of excessive drift or contamination. Finally, it applies stringent thresholds on isolation metrics to classify units as single or multi-unit activity.

The toolbox offers interactive visualizations and a graphical user interface (GUI) for exploring metrics and adjusting thresholds. It seamlessly integrates with popular manual curation software like Phy, enabling a flexible semi-automated workflow. Bombcell is optimized for efficiency, with rapid runtime and automatic plot generation at each stage. Users can quickly adjust parameters based on their specific needs using summary plots and the GUI. Bombcell's outputs are saved in a simple format, allowing users to easily modify classification criteria without recomputing metrics, promoting unbiased threshold selection.

## Project Author(s)
Julie M. J. Fabre

## Project Links
https://github.com/Julie-Fabre/bombcell

## Project Video
{{< youtube CvXUtGzkXIY >}}

***
This post was automatically generated by
anonymous
***