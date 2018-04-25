---
title: "Dual Beam Terahertz Time-Domain Spectroscopy"
layout: post
date: 2017-04-01
tag: data scraping, transactions
image: https://i.pinimg.com/originals/5f/9a/43/5f9a432cc5037901db54329657555f9a.jpg
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Terahertz spectroscopy"
category: project
author: eemelierkkola
externalLink: false
---


For my final year project I designed an optical setup to run a dual beam spectroscopy experiment in the terahertz time domain. Terahertz spectroscopy is a non-destructive way to study properties of matter using electromagnetic fields, and has applications for investigating superconductor properties, plasmonic effects in conducting materials, and rotational states of molecules. The module I built used a beamsplitter to split a femtosecond laser pulse into two parts: one to run through an electro-optic crystal with no additional material, and another to run through a material to be studied placed on top of the electro-optic crystal. The use of two beams allows for synchronous measurements to be made, decreasing systematic errors and allowing for the investigation of material properties by studying the relative differences in intensities and beam shapes of the output beams.

To measure beam profiles, Python scripts were used to automate the movement of a razor blade across the beam path to allow for a Gaussian beam profile to be built using the measured intensities during the movement of the blade. To shift the split beams in the time domain, two mirrors mounted on a motorised stage were also moved with automation using Python scripts. A picture of the setup is included below:

![setup](/assets/opticalsetup.png){:class="img-responsive"}
<figcaption class="caption">A detailed view of the optical set-up built for dual beam THz spectroscopy. The delay stage consists of two mirrors mounted on a motorised stage, where adjusting the position on the stage allows for time-delay measurements to be made.
</figcaption>


Follow this [link](https://www.dropbox.com/s/qif8pp6cgctbq42/Dual%20Beam%20Terahertz%20Time%20Domain%20Spectroscopy.pdf?dl=0) to read the full report.

---

Skills:

- Terahertz time-domain spectroscopy
- Python

---

