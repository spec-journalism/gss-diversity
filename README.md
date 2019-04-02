**How diverse is the science and engineering graduate student population?**

## TODOs

Is sex diversity in a certain field skewed by a certain race/ethnicity, citizenship, or another demographic characteristic?

Narrow down.
* Find which detailed fields influence/skew which broad fields the most
* Find people in these specific areas

Compare.
* Compare sex and race/ethnicity diversity to peer institutions
* Narrow down which detailed fields influence which broad fields the most

## Setup

1. Run `pipenv shell` to enter the virtual environment subshell
2. Run `jupyter notebook` to start your local notebook server

## General steps

1. Data collection: Export csv with data you want from [interactive](https://ncsesdata.nsf.gov/ids/gss)
2. Data cleaning: Read in that csv to pandas, and format it in a nested dictionary.
3. Data exploration: Use matplotlib to explore diversity over the last twenty years for every field (see [subplots](https://matplotlib.org/gallery/subplots_axes_and_figures/subplots_demo.html))
