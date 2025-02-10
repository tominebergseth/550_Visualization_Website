# 550_Visualization_Website

This website is a part of a semester long project in DSCI 550 at USC where we were assigned
a dataset from the Bigfoot Field Researchers Organization to work on cluster, featurize, visualize, and
analyze the data throughout the semester. The website features five D3.js visualizations to showcase
some of this work.


# Credits
I (Tomine Bergseth) created the website as well as the interactive line chart visualization. Ariel Martinez
made the map visualization, Devashish Sonawane made the nested circles visualization, Willy Tang did the 
bubble chart visualization, and Ekaterina Shtyrkova did the word cloud visualization. Our final team member
was Kyosuke Chikamatsu and worked on other parts of this particular assignment.
I also want to credit the 2018 version of this class, whose git website for UFO data, I followed and used
as a template: https://github.com/USCDataScience/ufo.usc.edu/tree/master as well as professor Christian Mattmann
who assigned this project.



# Notes on website code folders:
- The html folder has all of our html files for visualizations
- The css folder has css code I took from the template
- The json folder has our json data for the visualizations
- The js folder has js code I took from the template corresponding to features such as scrolling abilities
- The images folder has our front page image, logo, and thumbnail images.
- The index file outside the folders follow the one in the template with updates for ours and provides the
  structure and basis of the website.

# How to view the website:
- There is a live version of this website hosted on git pages: https://github.com/USCDataScience/ufo.usc.edu/tree/master
- Alternatively, to view this website locally with some minute updates:
  - Download this git directory
  - From the command line, navigate to the folder where you installed this project: cd path/to/folder
  - Open a python server: python -m http.server 8000
  - From a server, open http://localhost:8000/
  - Navigate between the different website pages to interact with the different visualizations and functionalities.




