+++
title = "SHARCC"
date = 2024-01-01
summary = "Colour Correction Of Augmented Reality Objects Using Spherical Harmonics Lighting"
main_image = "images/sharcc/spherical-harmonics-demo.gif"
categories = ["personal"]  # optional
tags = ["rendering", "dx11"]  # optional

[params]
  featured = false # Show in featured section on homepage
  weight = 2  # Order in featured section (lower = first)
  showInPostList = false # Show in timeline lists alongside blog posts
+++



This project was made in cooperation with [LUGG](https://graphics.cs.lth.se/). They provided me with a HoloLens 2 and source code for Rikard Olajos’s ARCC, which was the base for this project. During my work I gained a better understanding of the importance of lighting in 3D simulations, and how big of a role Spherical Harmonics have played over the years in that field. Great source on that topic is [Robin’s Green Spherical Harmonics Lighting: The gritty detail](https://www.cse.chalmers.se/~uffe/xjobb/Readings/GlobalIllumination/Spherical%20Harmonic%20Lighting%20-%20the%20gritty%20details.pdf). This was also my first experience with creating an UWP application based on DirectX 11.

{{< figure 
    src="images/sharcc/spherical-harmonics.png" 
    alt=""
    position="center"
    caption="SH projection of functions with increasing orders of approximation"
    class="post-image"
>}}

{{< figure 
    src="images/sharcc/spherical-harmonics-demo.gif" 
    alt="Two rotating spheres with changing textures. The one top shows original texture, and the bottom one is Spherical Harmonics reconstructions."
    position="center"
    caption="Limited band reconstruction of different cube maps"
    class="post-image"
>}}

### About the project 
While Virtual Reality headsets completely cut the user off the real world surrounding, Augmented Reality, as the name suggests, augments it by displaying virtual content on top of it, allowing user to still be fully aware of the real world environment. Being able to place and interact with digital objects on a physical desk is truly a mesmerizing experience for the first time users, that seems to bridge the gap between physical and virtual space. However, as the amazement wears off, one can notice that the digital objects are often easily distinguishable and appear to be out of place when compared with their real world equivalents. One of the main reasons for this phenomena is lighting of the virtual scene, which often does not fully match the lighting from the physical environment, hence rendered objects tend to stand out to the user. In this work I investigated colour correction of objects rendered in AR, in order to provide a way to seamlessly blend them with the environment, hence improving the realism and immersion for the user of HoloLens 2.
 
{{< figure 
    src="images/sharcc/desktop-diffuse.png" 
    alt=""
    position="center"
    caption="Desktop Application: Diffuse Shading with single Point Light "
    class="post-image"
>}}

{{< figure 
    src="images/sharcc/desktop-sh.png" 
    alt=""
    position="center"
    caption="Desktop Application: Spherical Harmonics Lighting"
    class="post-image"
>}}

{{< figure 
    src="images/sharcc/ar-noshading.jpg" 
    alt=""
    position="center"
    caption="HoloLens Application: No shading"
    class="post-image"
>}}

{{< figure 
    src="images/sharcc/ar-sh.jpg" 
    alt=""
    position="center"
    caption="HoloLens Application: Spherical Harmonics Lighting"
    class="post-image"
>}}
