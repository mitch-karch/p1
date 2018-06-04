---
weight: 1
title: "Within2 | Mitchell Karchemsky"
description: "I set a direction for the branding and identity of the product and crafted a functioning prototype ready for usability testing and development."
nav_heading: "Within2"
thumbnail: "zero9.jpg"
case_short_title: "Within2"
case_title: "Within2"
case_subtitle: "How do we create music we can feel?"
case_description: "Collaboration with Meyer Sound, The Berkeley Center for New Media, and Artist Tarek Atoui. How do we create music for the hearing impaired?"
case_feature_img: "zero9.jpg"
case_summary: "Within 2 was a project I worked on with Meyer Sound, The Berkeley Center for New Media, and Artist Tarek Atoui. We started with the question of How do we create music for the hearing impaired?"
team: ["Mitchell Karchemsky", "Tarek Atoui", "Greg Niemeyer", "Perin Meyer", "Andrew Frankel"]
roles: ["Initial Prototyping", "Idea Exploration", "Product Manufacturing" ]
methods: ["Prototyping","Iterative Design", "Sketching", "3D CAD", "Software Programming"]
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

![](/studies/w2/zero9.jpg)

# Background

Within 2 was a project I worked on with Meyer Sound, The Berkeley Center for New Media, and Artist Tarek Atoui. We started with the question of "How do we create music for the hearing impaired?" A quote by Stanford Professor Anne Fernald guided me throughout the project:

> "Sound is touch at a distance." 

How can we rethink music in such a way that brings it to a more visceral physical sensation? 

Tarek worked with a school for deaf children and ran an experiment where the children were told to go to the city and record the sounds of things they like, which sounds like a fools errand of sorts. What he found is that they would record the sounds of motors and pumps which would vibrate and hum at low frequencies. When interviewed, they noted that they liked how they could feel the sound. 

This required lots of different creative thoughts but after weeks of work, we found that low frequencies, sub 100hz leading into what is called *infra-base*, when amplified propagates powerful waves which feels like a punch when you stand in front of a speaker. 

## We took this concept and broke it into two seperate instruments: 0.9 and SuperPac 

# SuperPac

![](/studies/w2/pac.png)

The SuperPac is a direct translation of sound to physical sensation. Utilizing special chairs with built in resonating transducers, the chair serves as the physical interface between the sounds generated and the participant. We needed a way to create signals for the chairs to play and so I was tasked with the work of designing a texture board. Essentially a table with a 4x4 grid of specially textured wood boards which can be stroked and rubbed with special contact microphones to generate tones of different timbres. Three special tables with different physical interaction modalities were made allowing for the artists to not only play but to perform with their full bodies and having the physical motions directly for the observer to experience. 

# 0.9

Zero point nine was heavily influenced by Ernst Chladni and his famous work on standing waves and vibratory plates. Chaldni found that placing sand particles on a plate and having the plate resonate would create standing waves, or still points at certain areas of the resonating medium. We wanted to take this effect of standing points in a wave and expand it to a concert hall. With help from Meyer sound, we created 3 platforms consisting of 3 extremely powerful sub-woofers which would produce sounds ranging from 8hz (below the audible level of 20hz ) to 120hz. With these powerful speakers we filled two separate concert halls, a performance auditorium at Mills College, and Hearst Memorial Mining at UC Berkeley. This created a more interactive experience where people explored the space and found areas in the respective buildings where the physical feeling the difference in resonant frequencies in the floor, pillars, glass windows, and even the air around them. 

![](/studies/w2/z2.jpg)

With the heavy inspiration from the children that Tarek interviewed, we wanted to bring in a component of gestural languages as a medium for art. To do this, we utilized the powerful hand and gestural detection platform of the Leap Motion Sensor. Working closely with CNMAT, we interfaced the sensors to the speakers using MaxMSP and a custom built library to help our performers get a more intuitive sense of the gestural language of the instrument. 

![](/studies/w2/w2h.png)

You can read more about it [here in this press release](/Atoui_PR_Final.pdf)