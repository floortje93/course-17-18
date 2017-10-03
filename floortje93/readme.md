# Assignment 1  - Floortje Nijdam

This is a readme for the bar chart assignment of class 1

## Background
For this assignment, I had to choose a simple barchart from the d3 gallery on Github. 
I copy pasted the files of the chosen barchart into Atom. The first file was HTML with inline css and inline js. The second one was a .tsv file. 
I created new files for the css and the js so they were external files instead of inline code. I then linked the css and the js to the html with a <link> tag and a <script> tag.

Now its time to change some values so I could make the barchart mine. I changed the values in the .tsv file so the length of the bars changed.
I tried to change the color of the bars but somehow this did not work. Turns out I had to disable my cache. Now it works. I changed the colors and added some style to the <cite>.


## Data
The bars dont have a special value. They're just numbers and letters. To give you an idea what this bar chart could be used for, I made it an expenditure-income chart.
Gold stands for the expenses of a person and darkorchid shows you the income. 
![click here to see the Bar chart](https://prnt.sc/gsshc9).

* **Format:** it is a Bar Chart with positive and negative values.
* **Columns:** A,B,C,D are the expenses and E,F,G,H respresents the income. The horizontal line represents the amount of euro's spended or received.
* **Field:** So the vertical line represents the expenses (in lets say 4 days) and the horizontal line represents the income. 

## Features
* d3-extent — d3.extent — Both values at the same time
* d3-scale — d3.scaleOrdinal — Position encodings
* d3-selection — d3.select — Select elements
* d3-svg-axis — d3.svg.axis — renders human-readable reference marks for scales
* d3-tsv — d3.tsv — Loading external data

### License
MIT © 2017 Bar Chart, by Mike Bostock. (https://bl.ocks.org/mbostock/2368837)
