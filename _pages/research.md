---
permalink: /research/
layout: single
title: Projects
author_profile: true
toc: true
---

Current projects and collaborations

<h2 id="speculative">Speculative Scheduling</h2>

Reservation-based batch scheduling using priority
queues and backfilling algorithms is the current de facto
solution in implementing HPC schedulers. These systems
are designed for traditional scientific applications and can
have suboptimal performance for new emerging classes of applications.
These applications develop modeling and simulation workflows with unpredictable
resource requirements and focus primarily on productivity and not performance
(like neuroscience and bioinformatics).

This project focuses on the differences between typical HPC
scientific applications and stochastic workflows in order to design
at implement new computational models for engaging resources at
massive scale in novel ways to accommodate the specific needs.

<h3 id="scheduleflow"> Simulator </h3>

<img src="../assets/images/schedule_flow.png" align="left" alt="Schedule Flow" width="250"/>

For our experiments we built a simulator for HPC scheduelers, called [ScheduleFlow](https://github.com/anagainaru/ScheduleFlow).

The ScheduleFlow software consists of a series of scripts and classes that offer an API allowing users to create simulation scenarios for any type of online and reservation-based batch schedulers. 

<h2 id="io">I/O congestion</h2>

Many scientific HPC applications generate or deal with 
TeraBytes of data during their lifetime (for example, 
the Large Hadron Collider generates
15PB/year, light source projects deal with 300TB of data
per day and climate modeling are expected to have to
deal with more than 100EB of data). 
Moreover, I/O throughput and memory access time has an order of 
magnitude slower increase rate than FLOPs for the new 
generation of supercomputers. 

To help with the ever growing amount of data created,
architectural improvement such as burst buffers
have been added to the system. In addition, work is being done
to transform the data before sending it to the disks
in the hope of reducing the I/O sent. However, observations show 
that I/O transfer can still be slowed down up to 70% due to congestion
on current HPC systems.

This project investigates different optimization solutions 
to be included in the I/O middleware in order to alleviate 
the impact of congestion on applications.

<h2 id="resiliency">Fault tolerance</h2>

HPC sysytems today contain more than 100,000 processing and memory units.
With an individual MTBF (Mean Time Between Failures) for one unit of, one century,
an HPC system will encounter a failure every 9 hours in average, 
which is smaller than the execution time of many HPC applications.
In addition to fail-stop failures, silent errors are not detected immediately,
but instead after some arbitrary detection latency can cause applications 
to degrade their performance, crash or reach a false result. 

This project investigates performance variability issues and
resiliency properties of scientific applications and HPC systems.
We are working on understanding the intrinsic applcication resiliency to
silent errors and how to leverage it to optimze the amount of resources
required by a successful run (for example, by decreasing the precision of 
computations and reducing the energy and memory footpring of an application)
The project also includes designing new fault tolerance methods by 
including preventive methods based on hardware counters and
application memory, network and computational patterns to optimizing 
current checkpointing strategies.

<h3 id="software">Software</h3>
HELO

