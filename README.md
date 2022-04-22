# The Mystery of Microsoft Movie and Streaming Division

**Author:** Grant Edwards

## Overview

Microsoft wants to launch a new streaming and movie division to compete within the theatric box office and home entertainment industry that has high potential to generate revenue but is a competitive industry. To support the launch, we have analyzed data from past movies to find the best genres Mystery and Horror, with high return on investments and low cost of production. May would be an ideal launch month as it historically has a lower number of releases and the highest ROI. We also found that James Wan, David F. Sandberg, and M. Night Shyamalan would all make great directors for our starting films with their experience and success in these genres.
***

## Business Problem

Microsoft wants to start a new streaming and movie division to compete with the likes of Netflix, Hulu, Amazon, Apple, and other major streaming services after seeing competitors’ various success in the field and it is good for large businesses to expand into a variety of industries as to have a more diverse portfolio. The theatric box office and home entertainment is a $100 billion dollar industry (variety, 2022). With a sector this large and with high potential return on investment, it would be a great opportunity for Microsoft to achieve an additional source of revenue for Microsoft, it will be another means to reach more potential customers for other sectors of the organization. 

To find where to start this new division we will be answering the following questions:


* What is the best genre of movie to start with?
* When would be the ideal release date?
* Who should be chosen as the director for the film?

To accomplish this, we will be using data from IMDB, Rotten Tomatoes, TheMovieDB and The Numbers.

Breaking into the theatric and home entertainment industry can be difficult with many big competitors already established and can have large cost of entry, with many films costing tens or even hundreds of millions of dollars to produce. The reason why we are focusing on these key points is that we can find the best genres to break into the industry without high costs of production, when to launch our program, so that we are not getting lost in a sea of compaction, and finding a director who has already found success in the genre and the industry to give us a solid backbone to get off to a good start. 
***

## Data

The data we will be using for this project comes from Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB and The Numbers. It contains information on movies, such as: the key personal involved in producing the films, reviews, and financials.
The key factors that we will be using to find achieve our goals of best genre, time of release and ideal director will be the financials of the movies (global gross and production budget), the release month of films and how films perform in each month, and who directed the most successful films in the genre that has the most potential. This should leave s with a solid starting point to break into the cinematic industry. 

The most important data we will be looking it is the financials. Besides global gross and the production budget, we will look at profit (global gross – production budget) and the return of investment (ROI = (profit/production budget)*100). There are other factors that we will not be going into that are not factored into this (such as advertising and other expenses). 
***

## Methods

Describe the process for analyzing or modeling the data. For Phase 1, this will be descriptive analysis.
We starting by getting the needed data into DataFrames.
Most of the innitial data was not too useful on its own, so DataFrames were combined using SQL.
The data was cleaned, finaincial strings were converted to floats, duplicated and missing data was removed.
Created new columns for profit and ROI. 
Graph data using matplotlib and seaborn. 
***

## Results

We found that Mystery and Horror are both high ROI genres with low cost of production and would make ideal starting genres for a new movie to start this program.
For the release month May had both the highest ROI of all months and a lower number of release dates making it an ideal launch Month.
We also found that James Wan, David F. Sandberg, and M. Night Shyamalan would all make great directors for our starting films with their experience and success in these genres.

***
Questions to consider:
* How do you interpret the results?
* How confident are you that your results would generalize beyond the data you have?
***

Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/viz1.png)

## Conclusions

These results should help us get a good starting position for a new streaming and movie division, creating a solid foundation and giving owners and investors confidence in our high rate of return for the first couple of films. This should lead us to more higher budget films in the future but this would be the best starting course of action and good short term goals. In the event that a movie does not perform well, the lower cost will be easier to bare. I am confident that this will lead to a string start in the launch of a new division. 

If we procced in this direction it would be good to look at writers, and other key personal for the films. We could also capitalize on other division of Microsoft (such as gaming) to find film ideas, or even look outside the organization, such as at novels and original screenplays. 

Potential issues include potential missing or incorrect data, as well as outdated data. There is also far more factors that affect the success of a movie and streaming services. It would be good to dive deeper and get more in-depth information about the films and consider other factors. 
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact **Grant Edwards, grantedwards11@gmail.com**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── micro-movie-project.ipynb           <- Narrative documentation of analysis in Jupyter notebook
├── micro_movie_presentation.pdf        <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
