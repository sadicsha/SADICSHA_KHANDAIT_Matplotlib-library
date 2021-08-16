 Matplotlib-library for Python and its numerical extensions NumPy. 
 Majorly used in two ways
1) Explicitly create figures and axes, and call methods on them.
2) Rely on pyplot to automatically create and manage the figures and axes, and use pyplot function for plotting. 
matplotlib.pyplot is a collection of functions that make matplotlib work like MATLAB. Each pyplot function makes some change to a figure: e.g., creates a figure, creates a plotting area in a figure, plots some lines in a plotting area, decorates the plot with labels, etc.

In matplotlib.pyplot various states are preserved across function calls, so that it keeps track of things like the current figure and plotting area, and the plotting functions are directed to the current axes (please note that "axes" here and in most places in the documentation refers to the axes part of a figure and not the strict mathematical term for more than one axis).
