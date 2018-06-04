---
weight: 1
title: "Bifröst | Mitchell Karchemsky"
description: ""
nav_heading: "Bifröst"
thumbnail: "bifro.jpg"
case_short_title: "Bifröst"
case_title: "Bifröst"
case_subtitle: "Better Embedded Systems Debugging"
case_description: "Berkeley Institute of Design. How do we better instrument embedded systems for combined software and hardware debugging?"
case_feature_img: "bifro.jpg"
case_summary: "Bifröst links the divide in embedded systems programming of hardware and software debugging. This work is published in UIST 2017"
team: ["Mitchell Karchemsky", "Will McGrath", "Daniel Drew", "Jeremey Warner", "Majeed Kazemitabaar", "David Mellis", "Björn Hartmann"]
roles: ["User Testing", "Paper Writing", "System Engineering" ]
methods: ["Prototyping","Iterative Design", "Software Programming"]
button_links:
    - link: "https://marvelapp.com/g4b64e/screen/14364499"
      img: "eyeball.svg"
      text: "View Prototype"
    - link: "http://copenow.co/"
      img: "eyeball.svg"
      text: "View Landing Page"
    - link: "cope.pdf"
      img: "download.svg"
      text: "Download Feature Sets"
testimonial: ""
testimonial_author: "John Robert Palomo"
testimonial_subtitle: "Co-founder, Cope"
date: 2017-10-15T03:29:08-07:00
draft: false
---

![](/studies/bifro/bifro.png)

# Abstract

A key challenge in developing and debugging custom embedded systems is understanding their behavior, particularly at the boundary between hardware and software. Existing tools such as step debuggers and logic analyzers only focus on software or hardware, respectively.   Bifröst is a new development environment designed to illuminate the boundary between embedded code and circuits. 

Bifröst automatically instruments and captures the progress of the user’s code, variable values, and the electrical and bus activity occurring at the interface between the processor and the circuit it operates in. This data is displayed in a linked visualization that allows navigation through time and program execution, enabling comparisons between variables in code and signals in circuits. Automatic checks detect low-level hardware configuration and protocol issues, while user authored checks test particular application semantics.  



<div class="videoWrapper" align="center">

<iframe width="853" height="480" src="https://www.youtube.com/embed/nEUb5j6LKag" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

</div>

### [You can read more about the work published here in the ACM Library](http://dl.acm.org/citation.cfm?id=3126658)