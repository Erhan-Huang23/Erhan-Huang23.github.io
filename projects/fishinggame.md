---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Two-player fishing game"
date: 2024
published: true
labels:
  - java
summary: "My team developed a finishing game a fishing game, which is a simple game where two people can fish. The player with a larger total fish length wins the competition."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

This fishing game is the last project developed by KCC campus using ICS 211 Java. It is a two player game where each player will have 12 opportunities to fish using different methods. Some methods are not allowed in specific seasons, and rules can be printed before each fishing start. Some caught fish are too small to fit into the bag, so it is necessary to decide whether to put the fish in the bag or let them leave each time. Players who use illegal fishing methods or put illegal fish in the bag will lose the game after 3 times, and after 12 times, the player with the higher total length will win. There are three people in my team responsible for classifying fish.
Here is some code that illustrates how we read values from the line sensors:

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

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
