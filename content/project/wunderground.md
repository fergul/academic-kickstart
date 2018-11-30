
+++
# Date this page was created.
date = 2017-10-27T00:00:00

# Project title.
title = "Wunderground"

# Project summary to display on homepage.
summary = "An android mobile app for alerting sleepy passengers of their impending stop."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "wundergroundHome.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["web", "systems", "java", "android", "smart-city"]

# Optional external URL for project (replaces project detail page).
#external_link = "https://github.com/fergul/chibiWebC"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"


[[gallery_item]]
album = "2"
image = "wundergroundHome.png"
caption = "Wunderground Home activity"
    
[[gallery_item]]
album = "2"
image = "wundergroundAlarm.png"
caption = "Wunderground Alarm activity"
+++

An android mobile app for alerting sleepy passengers of their impending stop.
Built after I grew tired of falling asleep and missing my stop on the way home from a long day (excuse the pun :D).

The app monitors WiFi access-points available on London underground station platforms, recording a user's progress towards their target location, i.e., home. As they approach their station the phone alerts the user in the hope they will wake up and realise. Currently prototyping using additional data and sensor fusion to improve station prediction accuracy using average time-between-station times and motion sensors to detect when the trains stops.

{{< gallery album="2" >}}