---
permalink: /talks/2024-06-26-scheduling
layout: talk
title: "Strategies for querying large-scale scientific data"
author_profile: true
toc: false
classes: wide
collection: talks
type: "Invited Talk"
venue: "17th Scheduling for large-scale systems workshop"
date: 2024-06-26
location: "Aussois, France"
tags: ['Queries', 'Scheduling']
---

My presentation focuses on efficient strategies for querying large datasets, specifically addressing quantities of interest and derived data.  Although not directly about scheduling, these strategies create analysis tasks and data transformation needs that can strain study resources, especially at scale.
To fully realize the potential of these data management and query techniques, and to ensure timely completion of analyses, the development and implementation of custom scheduling solutions will be essential.

<p class="archive__item-excerpt" itemprop="description">

<strong>Abstract:</strong>
Scientific data analysis often involves complex queries across distributed datasets, requiring manipulation of multiple primary variables and generating derived data that needs to be handled efficiently, creating challenges for applications that need to parse many large datasets. We investigate in this talk the performance of different approaches where applications define derived variables as quantities of interest (QoIs) and offload the computation and transfer of these QoIs to the I/O library. We look at a detailed analysis of the performance-storage trade-offs associated with different solutions and showcase results for our study
on two large-scale datasets created from climate and combustion
simulations.

<br/><br/>
Link to the event: <a href="https://graal.ens-lyon.fr/~abenoit/aussois24">https://graal.ens-lyon.fr/~abenoit/aussois24</a>
</p>
<strong>Related paper:</strong> To Derive or Not to Derive: I/O Libraries Take Charge of Derived Quantities Computation <br/>
A. Gainaru, N. Podhorszki, L. Dulac, Q. Gong, S. Klasky, G. Eisenhauer, A. Kougkas, X. Sun, J. Lofstead <br/>
2024 IEEE 36th International Symposium on Computer Architecture and High Performance Computing (SBAC-PAD), 105-115, 2024
