# lsoaplot
Python script to generate videos for England Covid 19 LSOA data

Tested on Ubuntu 20.04, using Spyder with Python 3.8

Calls convert and ffmpeg as os processes (eg sudo apt install imagemagick ffmpeg)
Requires matplotlib and csv libraries in Python (eg pip install matplotlib csv)

The latest LSOA data is currently (28/09/2020) available from:
https://coronavirus.data.gov.uk/downloads/lsoa_data/LSOAs_latest.csv

To run:
python3 create_lsoa_map.py
