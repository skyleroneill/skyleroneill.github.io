---
layout: post
title:  "Seam Carving"
date:   2019-01-17
feature: /assets/img/beachout.jpg
excerpt: "Content aware image resizing program."
project: true
tag:
- computer graphics
- seam carving
- UMBC
comments: false
---

## About this project

This project was done as part of a computer graphics course (CMSC 435 with Adam Bargteil) which I took at UMBC. The project description page can be found <b><a href="https://www.csee.umbc.edu/~adamb/435/proj6.html">here</a></b>.

The project involved implementing a content aware image resizing algorithm. This means a program that can resize an image to smaller dimensions, but still retain the most important information in the image.

As you'll in see the examples below, results are best on images with large simple backgrounds. Results are most hilarious (or creepy) on images of objects where every detail is important, such as faces.

## Examples
<figure>
	<a href="/assets/img/beach.jpg"><img src="/assets/img/beach.jpg"></a>
	<figcaption>Before. Image is 1600 X 1067.</figcaption>
</figure>
<figure>
	<a href="/assets/img/beachout.jpg"><img src="/assets/img/beachout.jpg"></a>
	<figcaption>After. Image is 1200 X 800. Good results, minimally noticeable.</figcaption>
</figure>

<figure>
	<a href="/assets/img/bald.jpg"><img src="/assets/img/bald.jpg"></a>
	<figcaption>Before. Image is 1038 X 1038. Let's see what part of my face the algorithm will remove.</figcaption>
</figure>
<figure>
	<a href="/assets/img/baldout.png"><img src="/assets/img/baldout.png"></a>
	<figcaption>After. Image is 750 X 750. A little bit too much off the top there.</figcaption>
</figure>

<figure>
	<a href="/assets/img/Brubbers.png"><img src="/assets/img/Brubbers.png"></a>
	<figcaption>Before. Image is 701 X 921. A nice picture of me and my brothers.</figcaption>
</figure>
<figure>
	<a href="/assets/img/brubbersout.png"><img src="/assets/img/brubbersout.png"></a>
	<figcaption>After. Image is 500 X 500. The stuff of nightmares.</figcaption>
</figure>
