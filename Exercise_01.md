# Exercise 1

This exercise is about
* learning some command line tools like `awk`,`sed`,`grep`,`jq` etc
* learning to plot some data without python (*gasp*)
* learning their limitations
* if you want try to do a first plot in python (don't worry going forward we will use python)

# Step 1

* Go to this URL 

https://simplemaps.com/data/world-cities

and download the Free Version of the World Cities data as a CSV file

# Step 2 

Look at the data using `cat`, `awk` etc to familiarize yourself with the structure of the data

#Step 3

* Develop a command line that starts with `cat data.csv | some more commands here`
that extracts all cities, where population information is available and where the
population is above some threshold number `N`. For example `N=1000000` (cities over a million inhabitants)

Use the command line to write the latitude and longitude data into a file `lat.dat`

#Step 4

* Familiarize yourself how to install the `gnuplot` tool.
* Figure out how to do a scatter plot of the data you have with gnu plot and output it as `postscript`
* Can you adjust it such that you can read the data from `stdin`
* Find a command line tool that can take `postscript` at `stdin` and convert it into a PDF

#Step 5

* Write a one-line command line pipeline that plots all cities with more than a million inhabitants
* Is it easy for you to change it such that it plots all cities in Germany?
