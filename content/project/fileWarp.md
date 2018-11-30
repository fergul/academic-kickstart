+++
# Date this page was created.
date = 2018-11-01T00:00:00

# Project title.
title = "File Warp"

# Project summary to display on homepage.
summary = "A data-over-sound file drop utility built in Electron and JS. Utilises quiet.js to discover local devices to drop to and initiate handshake, then transfers data via socket.io over TCP/IP."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "fileWarp.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["electron", "web", "sound", "HCI", "javascript", "socket", "human-centric"]

# Optional external URL for project (replaces project detail page).
#external_link = "http://github.com/fergul/filewarp"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = "catchThatBusTrainExample.jpg"
#caption = "My caption :smile:"

[[gallery_item]]
album = "1"
image = "fileWarp.png"
caption = "File Warp"
+++

A sound-based local file-drop utility for sharing files between devices within earshot of one another. Uses \textit{quiet.js} to discover and hand-shake between clients before transferring files over \textit{socket.js} and a shared network connection. Built on the Electron web-based platform, utilising a JavaScript front- and back-end and Material design.

{{< gallery album="1" >}}