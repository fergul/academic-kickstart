+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "Catch That Bus/Train"

# Project summary to display on homepage.
summary = "A bus, train and weather ambient display utilising a Kindle e-reader."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "kindleExample.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["python", "web", "travel", "smart-city", "smart-home", "ambient", "human-centric"]

# Optional external URL for project (replaces project detail page).
#external_link = "http://github.com/fergul/catchThatBusTrain"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "catchThatBusTrainExample.jpg"
#caption = "My caption :smile:"

[[gallery_item]]
album = "1"
image = "catchThatBusTrainExample.jpg"
caption = "Dynamic Ambient Transport Display "
[[gallery_item]]
album = "1"
image = "kindleExample.jpg"
caption = "Dynamic Ambient Transport Display "
+++

*Ever wanted to know if you needed to run to catch that bus or train...no, well I did!*

A simple ambient display to show bus and train times for a local stop, with weather info to let you know if you need an jacket on the way out.

Uses a kindle display to non-intrusively show info and looks great on its non-backlit e-paper display.

Written in Python utilising the MetOffice and TfL open data APIs to grab weather and transport information, respectively.

{{< gallery album="1" >}}