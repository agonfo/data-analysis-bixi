# data-analysis BIXI 

### Table of Contents

1. [Installation and Development Environment](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation and Development Environment<a name="installation"></a>

The libraries used are the common - pandas and matplotlib - for more information please refer to `requiremenst.txt`
- The code should run with no issues using Python 3.7
- The data used can be found [here](https://drive.google.com/open?id=1Cabtm9AxLu8sTDPrvHNEHOFshBfKwlPs)

The data should be stored in a fila call 'data' and was downloaded from Open data webpage of the City of Montreal in the following links:

- [Bixi data](http://donnees.ville.montreal.qc.ca/dataset/bixi-historique-des-deplacements)  - create folder name bixi
- [Counters](http://donnees.ville.montreal.qc.ca/dataset/velos-comptage) - create folder name velo
- [Mon-ResoVelo](http://donnees.ville.montreal.qc.ca/dataset/trajets-individuels-velo-enregistre-mon-resovelo) - create folder name mrv


## Project Motivation<a name="motivation"></a>

This project is the first exercice for Udacity Data science nanodegree program. I was interestested in using Bixi data to analize the following questions:

1. Is people really using bikes? 
2. Does Bixi should open during winter?
3. What are bikes used for?
4. Are there any stations that could run out of bikes?


## File Descriptions <a name="files"></a>

There are 8 notebooks available here organized by themes.
Note that to runing this code there should be a folders called 'data' and inside three folders called 'bixi' , 'mrv' , and 'velo'.
1. data_merge - This 3 notebooks merge data sets to create a csv file containing all the year. 
2. count_days - use to count the number of days of the analyzed period
3. data_exploration - 3 exploratory files that clean and explore data for each one of the data sets - to runing this code there should be a folders called data/bixi.
4. analysis_bixi - Exploratory Notebook that searching through the data to answer the questions listed in the Proyect Motivation Section.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@arturo.gonfo/why-go-to-work-by-car-when-you-can-share-a-bike-7554a122ebc2).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

feel free to use the code here as you like