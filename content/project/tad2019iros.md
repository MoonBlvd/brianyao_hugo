+++
# Date this page was created.
date = "2017-09-17"

# Project title.
title = "Smart Black Box"

# Project summary to display on homepage.
summary = "We are proposing a value-driven evernt data recorder for advanced and autonomous vehicles, called the Smart Black Box."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "publications/sbb2018tits.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["current"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true
# Optional featured image (relative to `static/img/` folder).
[header]
image = "publications/sbb2018tits.png"
caption = "The Smart Black Box pipeline. A deterministic Mealy mahcine is use as buffer management. The compressed simulation images are tested with object detection and semantic segmentation."
+++
We are proposing the pipeline of a value-driven evernt data recorder for advanced and autonomous vehicles, called the Smart Black Box.

The system captures raw data from on-board sensors (high-bandwidth sources such as cameras and LiDARs and low-bandwidth sources such as CAN Bus). The data is processs by some event detectors and the data value is computed from the information contect of the event. A deterministic Mealy machine is applied to determine when to start and stop buffering data according to data value, data similarity, and buffer size limitation. Each data buffer is compressed using a compression factor computed from a local buffer optimization (LBO) process. The LBO optimizes the trade-off between data value and storage cost. 

We evaluate the reproducibility of the Smart Black Box compressed data by applying them to computer vision tasks such as object detection and semantic segmentation. The result shows that the Smart Black Box records data with less than 10% of the original storage cost while the object detection and semantic segmentation tasks could still achieve over 90% mAPs.



