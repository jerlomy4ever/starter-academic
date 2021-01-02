---
title: RRT*
summary: Search for a collision-free path for the robot's arm.
tags:
- Motion Planning
- Control
date: "2020-11-18T00:00:00Z"

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

## Abstract
Computed a collision-free path for a robot’s arm with RRT* (rapidly-exploring random tree star) such that the arm
reaches the goal without hitting any obstacle. Created a plugin for OpenRAVE in C++ to accelerate.

The code repository is [here](https://github.com/jerlomy4ever/EECS598_MotionPlanning/blob/main/hw03/my_solution/myplugin.cpp).