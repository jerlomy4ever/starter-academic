---
title: Vehicle Control
summary: Compute control signal to drive vehicle on predefined track and avoid random obstacles
tags:
- Motion Planning
- Control
date: "2019-11-18T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
{{< figure library="true" src="corner.png" title="Fig. 1 The vehicle path at the corner. <br />The red dots are the central line of the track and the rectangle is the obstacle.<br /> The blue line is the vehcle path." lightbox="true" >}}

## Abstract
Simulated vehicle driving in Matlab to race on predefined track and avoid random obstacles. Applied bicycle model and MPC (Model Predictive Control) for motion planning.