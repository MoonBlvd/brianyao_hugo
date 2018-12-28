+++
abstract = "Autonomous vehicles require reliable and resilient sensor suites and ongoing validation through fleet-wide data collection. This paper proposes a Smart Black Box (SBB) to augment traditional low-bandwidth data logging with value-driven high-bandwidth data capture. The SBB caches short-term histories of data as buffers through a deterministic Mealy machine based on data value and similarity. Compression quality for each frame is determined by optimizing the trade-off between value and storage cost. With finite storage, prioritized data recording discards low-value buffers to make room for new data.
This paper formulates SBB compression decision making as a constrained multi-objective optimization problem with novel value metrics and filtering. The SBB has been evaluated on a traffic simulator which generates trajectories containing events of interest (EOIs) and corresponding first-person view videos. SBB compression efficiency is assessed by comparing storage requirements with different compression quality levels and event capture ratios. Performance is evaluated by comparing results with a traditional first-in-first-out (FIFO) recording scheme. Deep learning performance on images recorded at different compression levels is evaluated to illustrate the reproducibility of SBB recorded data."

abstract_short = ""
authors = ["Yu Yao, Ella M Atkins"]
date = "2018-10-26"
image_preview = ""
math = true
publication_types = ["1"]
publication = "IEEE Transactions on Intelligent Transportation Systems (Under review)"
publication_short = "T-ITS"
selected = true
title = "The Smart Black Box: A Value-Driven High-Bandwidth Automotive Event Data Recorder"
url_code = ""
url_dataset = ""
url_pdf = ""
url_project = "project/SBB/"
url_slides = ""
url_video = ""

[header]
image = "publications/SBB_FSM_diagram.png"
caption = "My caption :smile:"

+++

