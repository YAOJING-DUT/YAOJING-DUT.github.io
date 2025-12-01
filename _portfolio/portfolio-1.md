---
title: "PROJECT 1：Construction of the Drift Correction Module in the STORM System"
excerpt: "Short Description：Construction of the Drift Correction Module in the STORM System<br/>"
collection: portfolio
---

[CODE AVAILABLE](https://github.com/JingYao-OPTICS2023/drift-correction-OOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO)<br>
🕮<b>README</b>：<br>
&ensp;&ensp;Before imaging, focus the system and define this focal plane as 0. Then acquire a reference stack of 21 images from –1 µm to +1 µm along the z-axis with a step size of 0.1 µm, and save it to the REF path. After that, return to the focal plane, turn on the AUTO control button, and imaging can begin.<br>
&ensp;&ensp;For every 2000 frames acquired, an automatic drift correction will be performed. This process includes “turning on the white light, turning off the laser, capturing a bright-field image, calling MATLAB for computation, turning off the white light, turning on the laser, and controlling the PIEZO actuator to compensate for the drift.” The drift amount from each correction will be automatically saved to a text file and plotted as a curve in the RELATIVE DEPTH–TIMES panel.<br>
🧑🏻‍💻<b>ALGORITHM</b>：
<p align="center">
  <img src="/images/drift correction1.png" width="353" height="503">
  <img src="/images/drift correction2.png" width="353" height="278">
</p>
🛠️<b>TOOLS</b>：
LabVIEW-MATLAB、Serial Communications<br>
🍞<b>SOFTWARE</b>＆<b>HARDWARE</b>：<br>
<p align="center">
  <img src="/images/drift correction3.png" width="223" height="318">
  <img src="/images/shutter.png" width="518" height="318">
</p>
📹<b>VIDEO</b>：<br>
<video controls width="773" height="453">
  <source src="/images/dc video.mp4" type="video/mp4">
</video>
&ensp;&ensp;In general, the sample tends to drift in one direction. If the system is highly robust, the drift will fluctuate only within a small range.<br>
<p align="center">
  <img src="/images/drift correction4.png" width="353" height="353">
</p>

