# d3-parallel-coordinates

## Description
What is parallel coordinates ? Find out here http://en.wikipedia.org/wiki/Parallel_coordinates.
- Lines represent data points through 2 to N vertical axis. 
- Vertical axis do have the same height, but their scale is adapted to the data min and max.
- On hover on one line, the line change color to help identify it

## Controls
You have two controls :
- Number of lines : From 1 to 20, define the number of grey lines representing data through the different scales
- Generate random datas

For demonstration purposes, I picked 5 scales (a to e). You can add or remove some of them directly in the code to adapt to your datas.

## Improvements to be made
- Transitions are a bit messy
- Lines should evolve from the left to the right axis smoothly and all at the same time

![Alt text](https://github.com/agatheblues/d3-parallel-coordinates/blob/master/parallel-coordinates/parallels.gif "A gif that shows the different controls")
