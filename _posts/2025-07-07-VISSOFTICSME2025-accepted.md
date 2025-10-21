---
layout: page
title: VISSOFT/ICSME 2025
---

<h3>3 papers accepted at VISSOFT/ICSME 2025</h3>

The papers "Visualizing and Exploring Data Access in Microservices Using Interactive Treemaps" and
"Visualizing Data Access Traces in Microservices Using Animated Heat Treemaps" have been accepted to 
<a href="https://vissoft.io/2025/" target="_blank">VISSOFT 2025</a>, respectively in the main and the NIER tracks.

For its part, the paper "DENIM: Exploring Data Access in Microservices" has been accepted to
<a href="https://conf.researchr.org/home/icsme-2025" target="_blank">ICSME 2025</a> in the Tool Demo track.

In these papers, we present visualization approaches and a tool to support the understanding of data access in 
microservices architectures using interactive treemaps and heat treemaps.

The interactive treemap contributes in representing the data access code fragment of a microservice architecture in a 
compact and efficient 2D space. It helps in identifying technology breakdown patterns, analyzing the impact of data 
concept changes, comparing system versions to track evolution or refactoring scenarios, and highlighting particular 
code patterns. This approach can be used to aid in decision-making for refactoring and evolution 
strategies. We evaluated that approach on 10 non-trivial systems with 6 professional developers within 4 organizations 
and obtained encouraging feedbacks that we discuss in the paper.

The heat treemap aims to extend, as an overlay, the interactive treemap with dynamic instrumentation traces. The 
approach replays and draws the sequence of the calls using animations. It also colours the hotspots within the data 
access code fragments in order to highlight the hotspots. Through an efficient UI, the traces can be further inspected.
This promising approach brings more concreteness to the decision-making process when it comes to evolution and 
refactoring. We evaluated our approach on a case study: Overleaf. In a 6-days scenario, we collected more 
than 109K traces to visualize.

The tool is the materialized artifact resulting of this research.

Maxime will present these papers with his co-authors early September 2025 in Auckland (New-Zeland).

The papers have been co-authored with researchers of the <a href="https://reveal.si.usi.ch/" target="_blank">REVEAL 
research group</a> at <a href="https://www.usi.ch/en" href="_blank">Università della Svizzera italiana (USI)</a> in 
Lugano (Switzerland) where Maxime stayed 6 months. This collaboration is supported by the <a 
href="https://www.sofinaboel.be/" target="_blank">SofinaBoël Fund for Education and Talent</a>. The paper about the 
heat treemaps is the result of a collaboration with Maxime De Rycke, a master's student from the University of Namur.

<div style="display: flex; justify-content: space-around;">
    <img src="{{ site.baseurl }}/images/VISSOFTICSME-1.png" width="50%"/>
</div>
<div style="display: flex; justify-content: space-around;">
    <img src="{{ site.baseurl }}/images/VISSOFTICSME-2.png" width="50%"/>
</div>
<div style="display: flex; justify-content: space-around;">
    <img src="{{ site.baseurl }}/images/VISSOFTICSME-3.png" width="100%"/>
</div>