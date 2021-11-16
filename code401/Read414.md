# What we will learn

- Matplotlib tutorial 

The source of this summary [The first link](https://github.com/rougier/matplotlib-tutorial)

______________________________________

## Matplotlib tutorial

**matplotlib.pyplot is a collection of functions that make matplotlib work like MATLAB. Each pyplot function makes some change to a figure: e.g., creates a figure, creates a plotting area in a figure, plots some lines in a plotting area, decorates the plot with labels**


## Pyplot

*is an API (Application Programming Interface) for Python's matplotlib that effectively makes matplotlib a viable open source alternative to MATLAB. Matplotlib is a library for data visualization, typically in the form of plots, graphs and charts.*


## Changing colors and line widths

Example:

            
        plt.figure(figsize=(10,6), dpi=80)
        
        plt.plot(X, C, color="blue", linewidth=2.5, linestyle="-")
        
        plt.plot(X, S, color="red",  linewidth=2.5, linestyle="-")
        
         

## Moving spines

**Spines are the lines connecting the axis tick marks and noting the boundaries of the data area. They can be placed at arbitrary positions. See set_position for more information.**

Example:

          ax = plt.gca()
          ax.spines['right'].set_color('none')
          ax.spines['top'].set_color('none')
          ax.xaxis.set_ticks_position('bottom')
          ax.spines['bottom'].set_position(('data',0))
          ax.yaxis.set_ticks_position('left')
          ax.spines['left'].set_position(('data',0))


## Animations in Matplotlib

**Animations in Matplotlib can be made by using the Animation class in two ways: ... By calling a function over and over: It uses a predefined function which when ran again and again creates an animation. By using fixed objects: Some animated artistic objects when combined with others yield an animation scene.**

### we can make:

1. Drip drop

![Drip drop](https://github.com/rougier/matplotlib-tutorial/raw/master/figures/rain.gif)

2. Earthquakes

![Earthquakes](https://github.com/rougier/matplotlib-tutorial/raw/master/figures/earthquakes.png)


## Figures, Subplots, Axes and Ticks

> So far we have used implicit figure and axes creation. This is handy for fast plots. We can have more control over the display using figure, subplot, and axes explicitly. A figure in matplotlib means the whole window in the user interface. Within this figure there can be subplots. While subplot positions the plots in a regular grid, axes allows free placement within the figure. Both can be useful depending on your intention. We've already worked with figures and subplots without explicitly calling them. When we call plot, matplotlib calls gca() to get the current axes and gca in turn calls gcf() to get the current figure. If there is none it calls figure() to make one, strictly speaking, to make a subplot(111).

