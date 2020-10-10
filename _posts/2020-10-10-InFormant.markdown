---
layout: post
title: "InFormant"
date: 2020-10-10 10:38:24 +0200
categories: showcase
author: Clo 
---

# a software for voice analysis

[**InFormant**](https://in-formant.app) is an open-source application for voice power users which features pitch tracking, formant tracking, as well as an all-purpose spectrogram and an inverse filtered glottal flow estimation.

This project started as a pastime project amidst the spring of 2018 and progressively evolved into a powerful voice analysis *(and synthesis!)* tool.

There was a real need for an application like this to be created, as the existing tools were unsatisfactory in terms of features and user experience. InFormant endeavours to make voice analysis overall more accessible.

That is also what motivated the current business model: a personal use license which can be obtained for free or at any chosen price, and a fixed-price professional use license.

Of course, there is still a lot of ground work to be done in order to fulfill the ideals that this project was founded upon.

For instance I am still not satisfied with the performance and accuracy of the pitch tracking algorithm currently in use, [RAPT](https://www.ee.columbia.edu/~dpwe/papers/Talkin95-rapt.pdf) adapted for instantaneous pitch estimation.

I also want to eventually implement a more robust algorithm for glottal inverse filtering (I have my eyes on [AM-GIF](https://iopscience.iop.org/article/10.1088/1361-6420/aa6eb8)), as well adding a measure of breathiness, creak, and possibly also detect pathological voice cases.

For the time being though, I am focusing my efforts on improving the user interface and user experience, by working closely with the community.

— Clo Yun-Hee.
