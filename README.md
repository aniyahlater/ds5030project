# R&B Song Chord Generator
This project aims to produce a generator that can synthesize R&B song snippets based on chords used in R&B songs present within the Chordonomicon dataset for the purposes of a project for the DS 5030 class within the UVA MSDS program in the Fall 2025 semester.

## Contents
This repository contains instructions on obtaining and cleaning the data used, code that completes and outputs the result of the song generator, an outline of the methodology used within this project, and reference information.

## Software and Platform
This project was completed using the Python programming language within VS Code. The platform used was Windows. If using VS Code to reproduce results, a Python kernel will need to be used in order to use Python and import the packages used in the scripts.

## Documentation
Contents of this repository include:

- README.md: a file containing all information about the files within the repository

- .gitignore: a file detailing what files within the repository should be ignored by Git (it is empty in this case)

- DS5030 Project Final Outline: a PDF file outlining the methodology and thought process behind this project

- get_data.ipynb : a Jupyter notebook containing the code utilized for this project

## Reproducing Results
The data can be obtained from the following line in the Jupyter Notebook:

`df = pd.read_csv("hf://datasets/ailsntua/Chordonomicon/chordonomicon_v2.csv")`

All code to clean and process the data, as well as reproduce the results of the project, is included within the Jupyter Notebook. 

## References
[1] Kantarelis, S., Thomas, K., Lyberatos, V., Dervakos, E., & Stamou, G., "CHORDONOMICON: A Dataset of 666,000 Songs and their Chord Progressions," Oct. 2024. Accessed: Nov. 12, 2025. [Online]. Available: https://arxiv.org/abs/2410.22046
