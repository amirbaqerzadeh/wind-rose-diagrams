Wind-Rose Diagrams with Python

This repository contains Python code to generate wind-rose diagrams using the windrose library. The diagrams are based on wind speed and direction data collected at a synoptic station between 1990 and 2004, with the exception of 1998 which is missing.

Data Source

The wind speed and direction data used in this project was obtained from a synoptic station in Iran. The data consists of measurements taken every three hours between 1990 and 2004. The data was originally provided in a Excel file, which was cleaned and processed using Python and the pandas library.

Installation

To use this code, you will need to have Python 3 installed, along with the following libraries:

    numpy
    pandas
    matplotlib
    windrose

You can install these libraries using pip:

pip install numpy pandas matplotlib windrose

Usage

To generate wind-rose diagrams for each season between 1990 and 2004, run the commands in :

plot wind rose diagrams for data from 1990 to 2004..ipynb

This may take some time to complete, depending on the speed of your computer.

Once the script has finished running, the wind-rose diagrams will be saved as PNG files in the plots/ directory.
