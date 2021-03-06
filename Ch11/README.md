# Chapter 11
Chapter 11, **Stunning Visuals**, comprises of sundry approaches to plotting graphs including **line charts**, **bar graphs**, **scatter plots**, and **D3.js visualizations**.

This is the accompanying source code for [Haskell Data Analysis Cookbook](http://haskelldata.com).
Refer to the book for step-by-step explanations.

<p align="center"><a href="http://haskelldata.com" target="_blank"><img src="http://haskelldata.com/images/ch11.png"/></a></p>

# Recipes:
* **Code01**: Plotting a line chart using Google's Chart API
* **Code02**: Plotting a pie chart using Google's Chart API
* **Code03**: Plotting bar graphs using Google's Chart API
* **Code04**: Displaying a line graph using gnuplot
* **Code05**: Displaying a scatter plot of two-dimensional points
* **Code06**: Interacting with points in three-dimensional space
* **Code07**: Visualizing a graph network
* **Code08**: Customizing the looks of a graph network diagram
* **Code09**: Rendering a bar graph in JavaScript using D3.js
* **Code10**: Rendering a scatter plot in JavaScript using D3.js
* **Code11**: Diagramming a path from a list of vectors

# How to use
### Setting up the environment
Install the [Haskell Platform](http://www.haskell.org/platform/).

    $ sudo apt-get install haskell-platform

Alternatively, install GHC 7.6 (or above) and Cabal.

    $ sudo apt-get install ghc cabal-install

### Running the code
A `Makefile` is provided in each recipe. Compile the corresponding executable by running `make`.

    $ make

Run the resulting code. For example,

    $ ./Code01

To clean up the directory:

    $ make clean
