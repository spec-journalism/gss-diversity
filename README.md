# GSS Diversity

## Guiding questions

In Columbia, for every field, what has gender representation looked like in the last twenty years?

In Columbia, for every field, what has race/ethnicity representation looked like in the last twenty years?

## Setup

1. Run `pipenv shell` to enter the virtual environment subshell
2. Run `jupyter notebook` to start your local notebook server

## General steps

1. Data collection: Export csv with data you want from [interactive](https://ncsesdata.nsf.gov/ids/gss)
2. Data cleaning: Read in that csv to pandas, and format it in a nested dictionary.
3. Data exploration: Use matplotlib to explore diversity over the last twenty years for every field (see [subplots](https://matplotlib.org/gallery/subplots_axes_and_figures/subplots_demo.html))
