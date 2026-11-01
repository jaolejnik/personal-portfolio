+++
title = "Gradientlisa"
date = 2023-06-02
summary = "Exploration of Alternative Image Representation Using Signed Distance Functions"
main_image = "images/gradientlisa/monalisa/monalisa-rec.png"
categories = ["personal"]  # optional
tags = ["rendering", "SDF"]  # optional

[params]
  featured = true  # Show in featured section on homepage
  weight = 1  # Order in featured section (lower = first)
  showInPostList = true # Show in timeline lists alongside blog posts
+++

{{< photo-grid folder="images/gradientlisa/monalisa/" cols="2" >}}
 
This is the project for my Master’s Thesis, which I completed under the guidance of [EA SEED](https://www.ea.com/seed)’s Future Graphics team. I got to work alongside many industry veterans: Martin Mittring, Alan Wolfe, Jon Greenberg, Chris Lewin, and Colin Barré-Brisebois, just to name a few. Their vast knowledge and experience were of an incredible help.

### About the project 
This project leverages the core concepts of differentiable rendering to find alternative representation of images using geometric primitives rendered with Signed Distance Functions. By utilising gradient-descent-based methods it is possible to find optimal parameters of rendered primitives to create high-quality reconstruction. Moreover, this research serves as a foundation for extending the principles and methodologies explored to 2D space. While the project primarily focuses on 2D image representation, the insights gained can be applied to similar tasks in the field of 3D rendering. The project was build using C++, SDL and libtorch (PyTorch C++ API). If you would like to learn more, I strongly encourage you to read my published thesis [here](https://lup.lub.lu.se/student-papers/search/publication/9129143).

### Results
Here are some more reconstructions using various geometric primitives types and increasing number of primitives: 128, 256, 512, 1024 respectively.

{{< photo-grid folder="images/gradientlisa/womandarkhair/" cols="4" >}}
{{< photo-grid folder="images/gradientlisa/peppers/" cols="4" >}}
{{< photo-grid folder="images/gradientlisa/cameraman/" cols="4" >}}
{{< photo-grid folder="images/gradientlisa/mandril/" cols="4" >}}
