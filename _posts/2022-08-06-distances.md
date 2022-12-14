---
layout: post
title: "Distances and cosmology"
author: Lewys Richards
---

{% include math.html %}

Following the recent releases of the first images from JWST, there has been a lot of fantastic discussion and questions online relating to distances in cosmology. 
This is a topic that can be deceptively complicated, and as such there is often confusion and misconceptions regarding various concepts. 
In this post, I hope to clarify what astronomers mean when they talk about various distances, and how we can relate different concepts.

# The meaning of distance

To understand what astronomers mean when they talk about distances, we must first look at the various different definitions they might be talking about. For an in depth look at this topic, I recommend [David Hogg's post on distance measures](https://doi.org/10.48550/arXiv.astro-ph/9905116). 

The proper distance is quite easy to understand, it is simply the actual distance between the two objects at that time. 
As the universe expands, distant objects get further away from each other and so their proper distance changes over time. 
Cosmologists want a distance measure that doesn't change over time due to the expansion of the universe, and so they define the comoving distance, this relates to the proper distance by a parameter called the [scale factor](https://en.wikipedia.org/wiki/Scale_factor_(cosmology)): 

{% raw %}
$$
 D_{p}(t) = a(t) D_{c}
$$
{% endraw %}

Where $$D_{p}(t)$$ is the proper distance at time $$t$$, $$a(t)$$ is the scale factor at time $$t$$, and $$D_{c}$$ is the comoving distance. To keep things nice and simple, we say that the current value of the scale factor is 1 (with it being smaller in the past and greater in the future, as the universe expands), and this means that the current proper distance is equal to the comoving distance.

When discussing how far away something is, we can also discuss how long it has taken for the light to travel to us, we call this the look-back time or light travel distance. 
This is useful because we then know what age of the universe it is that we are looking at, given how long the light has taken to reach us. 
A look-back time of 10 billion years, for example, would mean that the light was emitted 3.8 billion years after the big bang (taking the big bang as happening 13.8 billion years ago). 
This corresponds to neither the distance that the object was when the light was emitter nor the proper distance now. 
If we wanted to know the distance that the object was when the light was emitted, we can multiply the comoving distance by the scale factor at the time of emission (which would give a value of 3.6 billion light years for a look-back time of 10 billion years).

# Measuring distances

There are various different ways of measuring distances in astronomy, with each having a typical range of distances over which the method is useful to us. 
Some of these methods are a direct measurement of distance (e.g. parallax or standard sirens), while others involve calibrating an indirect measurement using something that varies with distance (e.g. the apparent brightness of something with a constant brightness, called standard candles). 
The method of calibrating indirect distance measures using other distance measures leads to what we refer to as the "distance ladder" in cosmology, where we climb the ladder by calibrating measures that are more useful for long distances using measures that are only applicable to shorter distances. 

## Parallax

When you hold your thumb out at arms length and look at it with one eye closed, and then switch to the other eye, your thumb appears to change position relative to the background of further away objects. 
This is the concept of parallax, and you can use it to measure the distance to things. 
In astronomy, we look at the positions of stars (relative to further away background such as other galaxies) over time, and instead of switching eyes like we did earlier we make use of Earth's movement as it orbits the Sun. 
This is where we get the unit of distance called the "parsec" from, which is the distance at which a star will have a parallax angle of 1 arcsecond (which is a 60th of a 60th of a degree). 
Parallax is hence what we call a "direct measurement" of distance, as it is based only on some trigonometry.

The problem with parallax is that the further away something is, the smaller the parallax angle is and hence the harder it is to measure. This makes parallax only useful for stars that are relatively nearby (within the Milky Way or nearby [satellites](https://en.wikipedia.org/wiki/Satellite_galaxy) [of the Milky Way](https://en.wikipedia.org/wiki/Satellite_galaxies_of_the_Milky_Way)).

## Cepheid variables

WIP...
