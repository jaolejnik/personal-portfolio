+++
title = "NPR Renderer"
date = 2021-12-20
summary = "Implementation of a non-photorealistic renderer using OpenGL"
main_image = "images/npr-renderer/lego/lego-2-comic.png"
categories = ["personal"]  # optional
tags = ["rendering", "opengl"]  # optional

[params]
  featured = true  # Show in featured section on homepage
  weight = 2  # Order in featured section (lower = first)
  showInPostList = false # Show in timeline lists alongside blog posts
+++

This is the final project for Advanced Computer Graphics course at Lund University, on
which I worked with [Trevina Litchmore](https://www.linkedin.com/in/trevinalitchmore/). At
the course-wide competition it was voted as the best project by the jury consisting of
representatives from **AMD**, **NVIDIA** and **Ubisoft Massive Entertainment**.

{{< photo-grid folder="images/npr-renderer/sofa/" cols="2" >}}

### About the project
Realistic computer graphics were always associated with the most advanced technology and memorable experiences. Nowadays this is definitely still true, although the advancement in the field of 3D graphics is not as noticeable (especially by people outside the industry) as in early 2000s. This led to creators using unconventional ways to stylize their work, to make it more distinguishable from others. In the past, this stylization was often the consequence of hardware limitation, but today it is a conscious choice on part of the 3D graphics artist. Thus we wanted to explore this subject ourselves and came up with the idea to implement a non-physically based renderer that produces images that mimicked sketches. Additionally, we combined some aspects of the sketch renderer with diffuse shading and dithering to create a renderer that would output images in the style of the famous Pop Art artist, Roy Lichtenstein.

If you are interested in more in-depth explanation of the implementation I strongly encourage you to read our short report [here](https://raw.githubusercontent.com/jaolejnik/npr-renderer/main/TLitchmore_JOlejnik_NPR_Report.pdf).

{{< photo-grid folder="images/npr-renderer/lego/" cols="2" >}}

{{< figure 
    src="images/npr-renderer/sponza-pipeline-sketch.png" 
    alt="Hello Friend"
    position="center"
    class="post-image"
>}}

{{< figure 
    src="images/npr-renderer/sponza-pipeline-comic.png" 
    alt="Hello Friend"
    position="center"
    class="post-image"
>}}
