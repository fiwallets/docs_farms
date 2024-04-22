---
coverY: 0
layout:
  cover:
    visible: false
    size: full
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🌱 Seeds

Seed is one of the most important items in the farming game. They represent the resources needed to begin the process of growing and growing crops.&#x20;

Each type of seed may have its characteristics, such as growing time, yield, and commercial value.

<figure><img src="../../.gitbook/assets/seeds (1).png" alt=""><figcaption></figcaption></figure>

To determine the watering milestones and harvest time for plants in the game, based on the planting time and a coefficient calculated from the growth time :

<mark style="color:blue;background-color:purple;">**Growth Interval (GI)**</mark> **= Growing Time / 3 times**

<mark style="color:blue;background-color:yellow;">**Watering milestones**</mark> **= \[Planting Time + GI \* 0 , Planting Time + GI \* 1 , Planting Time + GI \* 2]**

<mark style="color:blue;background-color:orange;">**Harvest time**</mark>** = Planting Time + GI \* 2**

* **Growth Interval (GI)** The amount of time it takes for the plant to grow to the next level is referred to as the growth period or growing time. Determined by dividing the growing time by 3.
* **Watering milestones:** The times when plants need to be watered to grow. Players to water at the correct intervals, to ensure maximum growth and yield.
* **Harvest time** is calculated by adding "GI" to the planting time, multiplied by 2.

