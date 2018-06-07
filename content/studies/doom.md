---
weight: 5
title: "Doom Sense | Mitchell Karchemsky"
description: "Developed."
nav_heading: "Doom Sense"
thumbnail: "dom.jpg"
case_short_title: "Doom Sense"
case_title: "Doom Sense"
case_subtitle: "How can we feel information?"
case_description: "An experiment in haptic feedback modalities and sensory extension. We improved the performance of a player by delivering curated contextual information"
case_feature_img: "dom.jpg"
case_summary: "Doom Sense is an experiment in haptic feedback modalities and sensory extension. Our goal is to improve the performance of a player at the game DOOM, by delivering curated contextual information"
team: ["Mitchell Karchemsky", "Tomás Vega", "Aleks Kamko"]
roles: ["Initial Prototyping", "Hardware Design", "Embedded System Design", ]
methods: ["Prototyping","eagleCAD", "Embedded System Development", "Software Programming"]
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

# Doom Sense

Doom Sense was a project done in the class "Software Defined PCBs." The class focused on the idea of using software to define which components need to be utilized in order to bridge the gap in creating hardware. Being a student of Cognitive Science, I wanted to incorporate what I had learned about neuroplasticity to see how adding an additional sense modality would affect ones performance.

![](/studies/doom/dms.png)

We modeled our device around the first person shooter DOOM, where it is important to always be tracking what resources you have. For example, you would never want to be in a dark hallway with very low health. It also adds to the gameplay if you knew when enemies were somewhere not directly in your field of view.

![](/studies/doom/dom.jpg)

With these goals in mind, we created Doom Sense. Doom Sense is a jacket which a player would wear giving them a more immersive experience in a game. We focused on two data streams: Health, and proximity of enemies. We used a large dc motor with a offset counterweight to create vibrations. By scraping the data from the game of the remaining health, we could convert it to a percentage, with a percentage level, we modulate a waveform which simulates sinus rhythm of the heart; the less health you have, the faster and more aggressive the heartbeat is. The other data point we use is the proximity of enemies surrounding the player. We look for the closest enemy to the player that isn't in the direct field of view, calculate the distance and then with some trade-secret magic, convert distance information into pulse strength. We five motors on the neck of our jacket and found that most experienced video game players would adapt quickly and triangulate within the first 2 minutes of game play, while more novice players would take 5.