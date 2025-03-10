---
permalink: /talks/2023-05-22-scheduling
layout: talk
title: "Scheduling the I/O of AI applications with a focus on medical imaging"
author_profile: true
toc: false
classes: wide
collection: talks
type: "Invited Talk"
venue: "16th Scheduling for large-scale systems workshop"
date: 2023-05-22
location: "Knoxville, Tennessee"
tags:
  - Scheduling
  - Cancer research
---

My talk focuses on ways to build and automate AI workflows by separating the
data and computational planes and attaching tasks to data offloading
the I/O management to specialized processes. Experiments done on
a whole slide image processing workflow for cancer research shows
that the framework can leverage the data access and pre-processing
patterns in order to fetch in a more efficient way the required input
data in the needed format and ordered by the needs of each application
within the workflow.


<p class="archive__item-excerpt" itemprop="description">

<strong>Abstract:</strong>
Scientists are moving toward the creation of complex autonomous
workflows that rely on machine learning for various tasks.
Machine learning has been widely used for biomedical tasks and has
achieved remarkable success in many medical imaging applications.
However, biomedical imaging presents unique challenges that bring
a shift in the computational and I/O patterns expected by HPC systems.
The experimental nature of the studies and the high variety
in the sample types and modalities used for training which forces a
high variety of types of AI methods frequently leads to sub-optimal
performance when running on HPC. This talk looks at a new
paradigm for building and automating AI workflows by moving
tasks to data. The prototype framework we propose separates the
data and computational planes and attaches tasks to data offloading
the I/O management to specialized processes. Our experiments with
a whole slide image processing workflow for cancer research shows
that the framework can leverage the data access and pre-processing
patterns in order to fetch in a more efficient way the required input
data in the needed format and ordered by the needs of each application
within the workflow. Results on the Summit supercomputer
show an increase in the I/O performance of over 10x for a single
application run and a system wide throughput increase of over 2x
when running multiple applications concurrently.

<br/><br/>
Link to the event: <a href="https://icl.utk.edu/workshops/scheduling23/">https://icl.utk.edu/workshops/scheduling23</a>
<br/>
Access my <a href="http://icl.utk.edu/workshops/scheduling23/slides/sched23/Gainaru-2023_scheduling_gainaru.pdf">slides here</a>
</p>

<strong>Related paper:</strong><br/>
Profiles of upcoming HPC Applications and their Impact on Reservation Strategies<br/>
A Gainaru, B Goglin, V Honoré, G Pallez<br/>
IEEE Transactions on Parallel and Distributed Systems 32 (5), 1178-1190 <br/>
DOI: <a href="https://ieeexplore.ieee.org/document/9266751">10.1109/TPDS.2020.3039728<a/>
