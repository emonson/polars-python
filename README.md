# polars-python

*Except for the workshop materials listed below, 
right now this is mostly a work-in-progress repository. 
Many of the notebooks are old Pandas code that's been
translated into Polars code cells as a test, 
but they have not been properly documented for Polars
(meaning much of the markdown is still for the old Pandas content).*

## Visualizing with Polars + Altair in Python: a case study

Altair is the default visualization module if you're using Polars for data manipulation in Python. This will be a short case study presentation of how I used that combination of modules to solve a visualization problem. I'll start with a brief overview of the relevant Polars and Altair concepts and syntax, and then present an example where faculty in Engineering needed to visualize when the students they were advising were busy or had gaps in their combined schedules. The intent is to go beyond a typical example you'd see in a tutorial to see how someone used both Polars and Altair to solve a real-world problem.

### CDVS workshop – Fall 2025

- Slides HTML file: [HeatmapSlides.html](HeatmapSlides.html)
- Slides web version: [Quarto web slides](https://emonson.quarto.pub/visualizing-student-schedules-a172)
- Code notebook: [AdvisorStudentHeatmaps.ipynb](AdvisorStudentHeatmaps.ipynb)

