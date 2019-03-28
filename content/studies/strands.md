---
weight: 5
title: "Strands | Mitchell Karchemsky"
description: "Developed."
nav_heading: "Strands"
thumbnail: "stra.jpg"
case_short_title: "Strands"
case_title: "Strands"
case_subtitle: "How can we feel information?"
case_description: "An experiment in haptic feedback and sound generation; allowing performers to explore timbre, pitch, and volume through physical interaction"
case_feature_img: "stra.jpg"
case_summary: "Strands is an experiment in haptic feedback modalities and sound art. The goal was to explore timbre through a physical interactive modality"
team: ["Mitchell Karchemsky", "Tarek Atoui", "Greg Niemeyer"]
roles: ["Initial Prototyping", "Hardware Design", "Embedded System Design"]
methods: ["Prototyping","3D Modelling", "EagleCAD", "Embedded System Development", "MaxMSP"]

date: 2017-10-15T03:29:08-07:00
draft: false
---
# Strands
Strands was an extension of the Within 2 art project I collaborated with artist Tarek Atoui. In the exploration of generating different timbres and creating instruments which give physical feedback, I designed the Strand board. Emulating stalks of wheat in a field, you can stroke your hand through the acrylic rods, creating frequencies of different pitch(x direction), volume(y direction), and timbre(magnitude of oscillation created by spring back in the individual stalks). 

![](/studies/strands/stra1.png)

This instrument brought to life a concept which is hard to understand as timbre, often described as the color of a sound, is not something which a tangible qualia can be ascribed to.

![](/studies/strands/stra2.png)

For this a custom PCB was built that would: interface with 16 potentiometers to 6 Analog to Digital Converters, collate this data over SPI, transfer the information to an arduino microcontroller, which would then communicate over serial to MaxMSP to generate sounds.
