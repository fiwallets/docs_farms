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

**Dis = Growing Time/3**

**Watering milestones = \[Planting Time + Dis \* 0, Planting Time + Dis \* 1, Planting Time + Dis \* 2].**

**Harvest time = Planting Time + Dis \* 2**

* "Dis" is determined by dividing the growing time by 3.
* Watering milestones are calculated by adding "Dis" to the planting time, multiplied by 0, 1, and 2.
* Harvest time is calculated by adding "Dis" to the planting time, multiplied by 2.
