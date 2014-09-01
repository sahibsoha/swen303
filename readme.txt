Swen303 Information Visualisation System
By Sohaila Sahib
ID number: 300251410

How to run the system:
If using firefox:
-Open the index.html file from Firefox and then navigate using the menu at the top (in pink)

If using Google chrome or Internet Explorer:
You will probably need to use the terminal. 
-Type the following in the terminal "python -m http.server 8888 &" or "python -m SimpleHTTPServer 8888 &" depending on the version of python you have installed on the computer. 
-Then open up the browser (Google chrome or Internet Explorer) and type the following: http://localhost:8888/
-This should automatically load index.html

About the system:
There are two main features of this system: Interactive Scatterplots and Interactive Barcharts

-There is a scatterplot which filters by the 6 seasons, different points of the seasons (regular and finals) and different countries (NZ and Australia).
	 Hover over the points at any time on the scatterplot to see more information on the matches.

-There are bar charts to represent the performance of teams for each of the 6 seasons
-The sorted bar charts show a sorted version of this for better indication of final placings at the end of the season
-There are also bar charts indicating how the teams perform at specific parts of the season (including bar charts for early-season, mid-season, end of regular season)
	Hover over the bars for colour effects

Also here is a link to the license for the d3 library I have used:
https://github.com/mbostock/d3/blob/master/LICENSE

Note: If after downloading the submission the visualization isn't running then you have downloaded it in the wrong way, you need to right click and then "Save target as" for all files. 