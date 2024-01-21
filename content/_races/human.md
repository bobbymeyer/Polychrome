---
layout: race
author: ali-bobby
game: polychrome
content_type: race
splash_image: assets/images/races/human.png
title:  "Human"
name: human
tagline: "The Measure of All Things"
---

## Basic Attributes

Ability Score Increase
: Each of your ability scores is increased by 1.

## Description
Humans are a comparatively young, and the most numerous, race of intelligent humanoids on Oda.

### Versatility & Diversity
Humans are found in environment on Oda, from the frozen tundras of P'tlakeu to deserts of Xiyan. Humans are the most adaptable of Oda's intelligent humanoids, and because of that, they exhibit the greatest range of cultural diversity.

> In countless souls, a world of stories unfurls,
> Humans, myriad and vast, a whirlwind of pearls.

 
{% for subrace in site.subraces %}
{% if subrace.race == page.name %}

## *Subrace:* {{ subrace.title }}
{{ subrace.content }}

{% endif %}
{% endfor %}