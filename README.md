# bargraph
Python program to generate bar graphs (X11, PostScript, EPS) using my Python wrapper for the [g2 graphical library](https://sourceforge.net/projects/g2). It can optionally add one or more of the spline interpolations that I had added to g2 earlier (in C).

## Samples
Enter `fiveyears.py` and `bargraph.py -f -d tilburg -y 97` respectively for the EPS versions of these graphs:
![Monthly distribution of civil weddings in the Netherlands over the years 1994–1998.](https://github.com/tijs-m/bargraph/blob/main/Weddings_per_month_Netherlands_1994-1998.svg)
![A uniform cubic B-spline (yellow), a cubic Hermite spline (dashed), and a spline based on successive over-relaxation (orange).
Plotted is the distribution of civil weddings in Tilburg (954 in total) over the year 1997.](https://github.com/tijs-m/bargraph/blob/main/Weddings_per_month_Tilburg_1997.svg)

These plots first appeared in my doctoral dissertation (ISBN 90-9018145-8), on pages [29](https://commons.wikimedia.org/wiki/File:Weddings_per_month_Netherlands_1994-1998.pdf) and [139](https://commons.wikimedia.org/wiki/File:SplinesTilburg.pdf) respectively.
