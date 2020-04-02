# Airbnb Seattle Analysis (Udacity Project)

## Introduction

This is the first project of a Data Science Nanodegree with a topic of writing a data science blog post.

For this project, I have a mission to create a blog post and Github repository. Inspiration comes from [Robert's post](https://medium.com/@rchang)... Robert is a data scientist at Airbnb.

Main mission is to...

* Pose three questions of interested.
* Extract the necessary data to answer these questions.
* Perform necessary cleaning, analysis, and modeling.
* Evaluate the results.
* Share your insights with stakeholders who is represented by a technical audience.

Lets begin.

## Table of contents

- [Airbnb Seattle Analysis (Udacity Project)](#airbnb-seattle-analysis-udacity-project)
  - [Introduction](#introduction)
  - [Table of contents](#table-of-contents)
  - [Motivation](#motivation)
  - [Installation](#installation)
  - [File description](#file-description)
  - [Results](#results)
  - [Licence, Authors, Acknowledgements](#licence-authors-acknowledgements)
   
## Motivation

My dataset of choice is **Airbnb Seattle data**.

I will ask three relevant bussiness questions that hopefully, data will be able to answer. According to the questions, I will:
  * focus on right portions of the data available
  * handle and clean data issues, and provide insight into the way I approached solving  problems and why I selected these methods at the first place
  * visualize and analyze results 

## Installation

Local development setup:

* Windows 10 OS
* Visual Studio Code as an text editor and development environment.
  * python extension from VS code's marketplace
* Mini-Conda from which I used conda as package and environment manager.
  * in Anaconda Prompt run following to create correct python environment with all neccessary packages:
    * `conda create --name data-science-blog-post python=python=3.7.6 pandas=1.0.3 jupyter=1.0.0 matplotlib-base=3.2.1 seaborn=0.10.0 altair=4.1.0`
    * after setting up the environment run `activate data-science-blog-post`
    * clone the github repository to your local machine, open the cloned repo with Visual Studio Code's open folder, and choose correct environment `data-science-blog-post`.

## File description

This is project's file tree:

```
+---data
|   \---seattle
|           calendar.csv
|           listings.csv
|           reviews.csv
|
\---notebooks
|       seattle_airbnb_analysis.ipynb
|   .gitignore
|   README.md
```

* `data/seattle` - The Seattle AirBnB homes data. Downloaded from [kaggle](https://www.kaggle.com/airbnb/seattle/data). 
    *  `listings.csv` - including full descriptions and average review score
  *  `calendar.csv` - including listing id and the price and availability for that day
  *  `reviews.csv` - including unique id for each reviewer and detailed comments

* `notebooks/seattle_airbnb_analysis.ipynb` - jupyter notebook where I imported, prepared and analyzed the data
* `.gitignore` - files and folders to ignore for version control
* `README.md` - markdown document you are reading now :)

## Results

## Licence, Authors, Acknowledgements