---
layout: post
title:  AI Generated Artwork For My Website
date:   2022-07-08 18:05:55 +0300
image:  assets/images/blog/dalle_mini.jpg
author: Emil Skydsgaard
tags:   ai, dalle, images, web, artwork, generated
---

**I wanted artwork for my website and it had to be both unique and beautiful. Previously this sort of thing was hard to come by for free, but now it is simply a matter of asking an AI.**

After seeing how OpenAI's [DALL·E 2](https://www.instagram.com/dalle.2_art/) and Google's [Imagen](https://imagen.research.google/) are capable of generating stunning images from nearly any prompt, there can be little doubt that image generating AI is a technology that will be very influential in the future. As of now, there is a long waiting list to gain access to those fancy models, but it turns out that simpler (but much less capable) models are available for public use.

I stumbled upon a model called [DALL·E Mini](https://www.craiyon.com/) (now renamed to Crayion) which seemed to perform reasonably well if you tried enough times. A big caveat of this model is that the resolution of the output images is very small making the images quite useless as is. Once again AI comes to the rescue in the form of an AI image up-scaler – another technology that has seen impressive developments during the last couple of years. After trying out a bunch of them I settled on [this one](https://imgupscaler.com/) which seemed to perform the best. Combining these two tools I hence found a workflow that could generate interesting images in a decent resolution.

### My Results
The first thing I tried to generate was a pleasing background for the top banner of my website. I wanted something in warm colors that looked nice but didn't attract to much attention. After trying a selection of prompts I settled on ```sunset colored wallpaper``` which seemed to produce the kind of images I was looking for. After running the prompt about 10-20 times I had gathered a few promising low-resolution candidates. I selected my favorite, cropped it and passed it through the upscaler to obtain the following result, which is now in use across the site:

<img src="{{ site.baseurl }}/assets/images/backgrounds/sunset.jpg" class="img-fluid w-100 rounded">

For the site's favicon (and potentially other places in the future) I wanted a clean and minimalistic logo. Having no particular design mind I tried the following prompt: ```logo based on the letter E``` which produced a pretty inspiring variety of logo designs and within a couple of runs I had stumbled upon my new logo, which coincidentally matched the color scheme of the banner image:

<img src="{{ site.baseurl }}/assets/images/about/logo.jpg" class="img-fluid w-100 rounded">

The last thing I wanted to try was generating an interesting avatar for my GitHub page. I thought it could be fun to see what a ```bear programmer``` would look like, so I tried that prompt a lot of times and got many weird and abstract results. But a few of them were quite original and in the end I settled for this one, which I for some strange reason really like:

<img src="https://avatars.githubusercontent.com/u/58552146?v=4" class="img-fluid w-100 rounded-lg" style="clip-path: circle()">

### Wrapping Up
I had a lot of fun generating images and playing around with the prompts. Granted, it is nowhere near the quality of the top-tier models but for my purposes it did the job. In any case I would recommend trying it out for yourself, since writing prompts to an AI is probably something many of us will have to get used to sooner or later.
