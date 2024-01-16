---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "ZeroWaste App"
date: 2023-11-18
published: true
labels:
  - Recycling & Preservation Technology
  - App Development
  - HTML
  - CSS
summary: "My team (FireSheep) developed an application for the non-profit organization called Full Cycled Takeout that placed us as finalists in 2023 Hawaii Annual Code Challenge (HACC)."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

The Hawaii Annual Code Challenge (HACC) is an annually held event that challenges professional, amateurs, and students to create solutions for local organizations and the community of Hawaii. In 2023, FireSheep created a web application that kept track of reusable plastic containers that were borrowed by the local community to prevent excess waste from being created. There was a QR code and ID scanner to keep track of these reusable plastic containers, along with a user interface to easily select your preferences.

For this project, I was responsible for front-end development. As this was an application that allowed you to navigate multiple pages, I was tasked to make the user interface easily usable and to take into account how the user interface may function on your phone as opposed to a screen on a monitor. There were other people working on front-end development with me, so I had to also check their formatting and code, along with facilitating each of our tasks.

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

This is the associated page on [github.]([https://manoa.hawaii.edu/news/article.php?aId=2857](https://github.com/HACC2023/firesheep)https://github.com/HACC2023/firesheep).
