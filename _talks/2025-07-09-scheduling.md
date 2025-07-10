---
permalink: /talks/2025-07-09-scheduling
layout: talk
title: "On demand scheduling for large-scale workflows with analysis requirements"
author_profile: true
toc: false
classes: wide
collection: talks
type: "Invited Talk"
venue: "18th Scheduling for large-scale systems workshop"
date: 2025-07-09
location: "Montréal, Québec, Canada"
---

My talk for the 18th scheduling workshop workshop focuses on efficiently executing the analysis codes attached to large-scale simulations. These tasks require the data generated at every simulation step in order to extract knowledge (quantities or regions of interest), post-process data for training, to reduce or refactor parts of the data or simply visualize and audit the data. 

The increasing demand for computational resources, particularly for these analysis tasks attached to HPC simulations, necessitates to 
re-think how we handle job scheduling strategies. My talk addresses the challenge of managing concurrent jobs with differing priorities on limited compute resources and within a fixed time window and where strict QoS constraints are often difficult
for users to define. Our solution relies on a qualitative description of priorities and pulls from two key approaches: the Easy-BF algorithm and
the Conservative Backfilling algorithms.

Link to the event: https://perso.ens-lyon.fr/loris.marchal/scheduling-in-montreal/ <br/>
Link to my talk: [comming soon]

**This talk is based on the paper:** <br/>
Priority-BF: a Task Manager for Priority-Based Scheduling <br/>
Ana Gainaru, Scott Klasky, Guillaume Pallez <br/>
[EURO-PAR 2025-31st International European Conference on Parallel and Distributed Computing, 2025]
