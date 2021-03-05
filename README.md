# text_analytics-disneyland_reviews

## Overview

The jupyter notebook is developed to provide analytics solution from the reviews by disneyland visitors in three Disneyland theme parks located in California, Paris and Hongkong. The insights obtained from the analysis is used to provide recommendations to Disneyland management to improve their services and customer satisfaction. The data is extracted from the TripAdvisor website. The notebook provides an executive summary, data exploration, text analysis and practical implication from the analysis conducted. 

## Workflow

The following points details the workflow of this notebook:

* Finding the peak time for each theme parks.
* Finding the major groups of visitors.
* Finding the theme park with the highest ratings.
* Performing sentiment analysis to discover visitors' sentiments towards theme park aspects.
* Summary of approaches used.
* Detecting concerns and interests of visitors using topic modelling.
* Detecting the differences in concerns and interests of visitors between three parks.
* Finding the differences in concerns and visitors among major visitor groups.

## Prerequisites
* pandas
* numpy
* matplotlib
* sklearn
* nltk
* statistics
* collections
* re
* gensim
* seaborn
* wordcloud
* math

## Usage
The notebook uses reviews from Disneyland visitors and performs analysis of those texts. A similar kind of analysis on texts related to any topic can be undertaken to gather insights that may facilitate in taking further actions to improve the business or mission.

## Further Information
Problems can be encountered while viewing some files, such as the notebook and dataset. Cloning the repository on your local machine allows you to 
view the contents of all files in this repository. On the browser, the data can be viewed in raw format only. 
To see the notebook on your browser, one of the following methods may be taken:
1. Using Google Colab:
```shell
> open Google Colab using "https://colab.research.google.com/notebooks/".
> Select GitHub tab
> Paste the GitHub link containing your notebook and hit search.
```

2. Using Jupyter nbviewer:
```shell
> Open "https://nbviewer.jupyter.org/"
> Paste the Github link which contains the notebook file and click go.
```
Even after using these methods, you might encounter issues or delays. It is recommended to obtain a copy of files in your local system so that viewing and running the notebook become smooth.

#### Running the notebook
You may use the Jupyter notebook or Jupyter lab to run the .ipynb file. The main thing to remember is you must store both the .ipynb notebook file and the .csv file in the same folder path. Lastly, before running the notebook, you may need all the above mentioned required python libraries installed on your system, or you may install the libraries before executing the cell that calls any new libraries. 
