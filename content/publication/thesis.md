+++
title = "Towards Analysing Cyber Physical Systems in 3D Virtual Environments"
date = 2020-10-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Fergus William Leahy"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["5"]

# Publication name and optional abbreviated version.
publication = "Computing PhD Theses, Imperial College London"
publication_short = ""

# Abstract and optional shortened version.
abstract = """Design, development and deployment of cyber-physical systems (CPS), in particular human-centric CPS, is growing at a rapid pace, with the continuing downward trend in silicon costs and increasing demand for automation in the home, office, cities and national infrastructure, to cut costs, increase efficiencies and use less natural resources. Human-centric CPS can play pivotal a part in improving human well-being and safety, improve security and emergency evacuation, as well as helping us meet the worldwide targets for climate change set out by the Paris Agreement, involving the development and deployment of smart-homes, -cities and -countries developed by government, industry and academia, to reduce energy and resource waste.

However, simulating and analysing a human-centric CPS remains a challenging task, involving simulation of distributed systems in tandem with human-mobility, real-world physics and phenomena. 
Instead these simulations are often carried out in distinct disconnected tools, resulting in poor end-to-end testing and disjointed analysis of the CPS in different scenarios. 
Cyber-physical systems interact with the physical world, hence, poorly tested systems can cause more harm than good, damaging infrastructure, harming people and even risking lives when systems fail. 
Existing tools for simulating and analysing human-centric cyber-physical systems do not support real-time simulation of environments with dynamic human-mobility and phenomena-on-demand, instead only supporting static scenarios using recorded traces. 

In this thesis we present a novel cyber-physical system simulation framework for the simulation and analysis of human-centric cyber-physical systems. The framework utilises a video game engine to simulate the real world, create human-mobility of individuals and crowds that adapt to the environment, and generate phenomena-on-demand. The CPS is simulated using the Cooja WSN simulator, providing accurate and scalable simulation of deployable code. Using the virtual world within the game engine, we've developed a novel approach to analysing simulations, coined ``visual diffing'', enabling developers to visually compare the physical and virtual activity of two simulations simultaneously intuitively within the context of the visual simulation. 

We demonstrate the framework through two human-centric CPS case studies, which evaluate the problems of presence-based office lighting and dynamic fire evacuation navigation. Both problems rely upon the accurate simulation of the virtual environment, the human agents within it and the interaction between the cyber, physical and human aspects of the system. We demonstrate that the use of a game engine to simulate the real world, model human-mobility using behaviour trees and enable visual diffing, provides a feasible way to simulate and analyse human-centric CPS to test and discover differences between different simulated scenarios. We also evaluate the performance and trade-offs of realising this approach."""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project in `content/project/`.
#   Otherwise, set `projects = []`.
#projects = ["example-external-project.md"]

# Links (optional).
#url_pdf = "pdf/FergusLeahy-DejaVu-Paper-EWSN18.pdf"
#url_preprint = "#"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "http://hdl.handle.net/10044/1/83285"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "fireEvac.png"
caption = "A fire evacuation simulation running in Deja-Vu with visual diffing."

+++
