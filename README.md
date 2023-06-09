# Project Name

## Table of Contents
- [Project Name](#project-name)
  - [Table of Contents](#table-of-contents)
  - [Setup](#setup)
  - [Usage](#usage)
    - [Part 1:](#part-1)
    - [Part2:](#part2)
  - [Project structure](#project-structure)
<!-- * [License](#license) -->


## Setup

Create a conda env :

`conda create --name <env_name> python=3.7`

Activate it :

`conda activate <env_name>`

Install dependencies :

`pip install -r requirements.txt`

Make sure you have java jre installed and javapath added to environment variables (needed for Stanford dependency parser):

If you dont have it installed already, refer to : https://www.java.com/en/download/help/download_options_fr.html

Also, if you are running this code in windows, please download these two files :
- https://nlp.stanford.edu/software/stanford-corenlp-4.2.2.zip
- https://nlp.stanford.edu/software/stanford-corenlp-4.2.2-models-english.jar
- Copy them inside Part2/ and unzip stanford-corenlp-4.2.2.zip

If you are using linux the downloading and unziping is included in the notebook

## Usage
### Part 1:
Notebooks should be run in this order :
- data_collection.ipynb (can be omitted to avoid waiting for too long during scraping, output is in data_files directory )
- data_analysis.ipynb
- classification.ipynb

### Part2:
- part2.ipynb 

## Project structure

```
├── Part1
│   ├── classification.ipynb
│   ├── data_collection.ipynb
│   ├── data_analysis.ipynb
│   ├── clean_data.csv
│   ├── data_files
│   └── results
├── Part2
│   ├── part2.ipynb
│   ├── data
│   ├── segmentation_data.csv
│   ├── stanford-corenlp-4.2.2-models-english.jar
│   └── stanford-corenlp-4.2.2.zip
└── README.md
```
