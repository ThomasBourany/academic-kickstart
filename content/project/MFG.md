+++
title = "MFG"
date = 2018-03-17T17:40:29+01:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = "A reformulation of heterogeneous agents models with aggregate uncertainty as a typical 'Mean Field Game with common noise'"

# Optional image to display on homepage.
image_preview = "" #"static/files/All1_wealthdistrib.png"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

This project is part of my internship at Paris-Diderot University, under the supervision of Yves Achdou. 

The standard economic framework with "heterogeneous agents" -- the Aiyagari-Bewley model -- has recently been reformulated as an example of Mean Field Game (MFG), by Achdou, Han, Lasry, Lions and Moll (2018). One of the key question in this type of model is to understand the transmission effects of aggregate shocks - on aggregate macro variables and on the shape of the wealth distribution. Such framework can thus be understood as a MFG with "common noise". We simulate this model with a finite number of shocks, using specific finite-differences methods. We show that, in presence of aggregate uncertainty,  precautionary saving can have a large impact, smoothing the business cycle fluctuations. 

In these {{% staticref "static/files/Pres_MFG_MiMh.pdf" "newtab" %}} slides{{% /staticref %}}, I describe a preliminary version of this project 

In this report, I provide a complete description of the numerical methods implemented. 

