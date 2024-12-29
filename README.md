# Lyrics-Process-polars

## Overview

This project performs an in-depth analysis of song lyrics, focusing on text compression. By leveraging the Polars DataFrame library, it processes large datasets efficiently to explore various compression techniques and their effectiveness on song lyrics.

## Features

Data Loading: Reads and processes song lyrics and metadata.
Text Size Measurement:
Calculates the length of lyrics.
Determines the byte size of lyrics in UTF-8 encoding.
Compression Analysis:
Applies multiple compression algorithms, including gzip, zlib, and bz2.
Measures the compressed size of lyrics and calculates compression ratios.
Export Results: Outputs analyzed data to a CSV file for further exploration.
Technologies Used

## Python
Polars: High-performance DataFrame library.
Compression Libraries: gzip, zlib, bz2, and others.
Getting Started

Clone the repository and navigate to the project directory.
Install the required Python libraries:
pip install polars, pandas
Run the Jupyter Notebook or Python script to analyze lyrics data:
jupyter notebook Lyrics_Songs_Analysis_with_Polars.ipynb

## Input Data
CSV file containing:
song: Song title.
artist: Artist name.
genre: Genre of the song.
year: Release year.
lyrics: Full lyrics of the song.

##Output
CSV file with additional columns:
Length of lyrics.
Original size in bytes.
Compressed size using various algorithms.
Compression ratios.

## Descriptive Summary for the Notebook
Title: Lyrics Compression and process with Polars

This notebook explores the application of various text compression algorithms to song lyrics. By measuring the compression efficiency of different algorithms, it provides insights into how lyrical content can be optimized for storage or transmission. Key steps include calculating the original and compressed sizes of lyrics, deriving compression ratios, and exporting results for visualization or further analysis.
