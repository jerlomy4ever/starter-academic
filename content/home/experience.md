---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Robotics Engineer
    company: ADLINK
    company_url: 'https://www.adlinktech.com/en/index'
    location: Taipei, Taiwan
    date_start: '2020-06-01'
    date_end: '2020-08-14'
    description: |2-
        Responsibilities include:
        
        * Built mobile robot running under either ROS (Robot Operating System) or ROS2.
        * Simulated the robot with Gazebo to save time and evaluate the function I built.
        * Implemented LOAM (LiDAR Odometry and Mapping in Real-time) and UKF (Unscented Kalman Filter) with a Velodyne’s LiDAR, VLP-16, to lower the localization error of AMCL (Adaptive Monte Carlo Localization).
        * Accelerated AMCL with GPU by 30% while the pose error is about 50% less.
        * Replaced TEB (Timed Elastic Band) with DWA (Dynamic Window Approach) as the controller to rise the success rate of navigation by 20%.
        
  - title: Robotics Engineer
    company: Advanced Robotics
    company_url: ''
    location: Taipei, Taiwan
    date_start: '2018-11-01'
    date_end: '2019-04-30'
    description: |2-
        Responsibilities include:
        
        * Built an AGV (Automated guided vehicle) and implemented the system on ROS to deliver items in a hotel.
        * Generated the map with gmapping, laser-based SLAM (Simultaneous Localization And Mapping).
        * Localized the robot with AMCL and 2D LiDAR, RPLiDAR, while the initial pose is defined by AprialTag scanned by an RGB camera.
---
