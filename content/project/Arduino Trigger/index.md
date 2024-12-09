---
title: Arduino Camera Trigger
summary: Designed and built arduino-based camera trigger system
date: 2024-05-14
type: markdown
image:
  caption: ''
  focal_point: ''
  preview_only: false
reading_time: false
share: false
---

_Page Under Construction: photo coming soon_

I designed and built a system to synchronize and trigger cameras for experiments in the Queen's University large wave basin. The system is centered around an Arduino, which receives a start trigger from the wave paddle, waits for a specified duration, and then produces a square wave at a specified frequency via a power supply and relay. This output signal triggers the cameras for image capture. Additionally, the trigger system uses LED indicators to show the system status and is housed within a 3D-printed enclosure.

I also created an adapted version for use at the University of Wisconsin-Madison's Water Science and Engineering Laboratory wave flume. In addition to triggering the cameras, this version also synchronized the image capture with a data acquisition system, which captured wave height data from ultrasonic wave gauges and velocity data from Vectrino ADVs and ADV Profilers.

**Tools used**
- Arduino Uno and various components
- Soldered components for final assembly
- FMD 3D printing for enclosure