<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# AI Driven Movie Classifier

Building AI course project

## Summary

This project predicts the genre of a movie given its title.


## Background

This project solves the problem of identifying the genre of a movie when you only have its title.  Tinker Tailor Soldier Spy?  Eternal Sunshine of the Spotless Mind?  This project provides an AI suggestion to what sort of film these (or any other titles, real or fictitious) may be.  This topic speaks to my love of movies as well as my curiousity in AI.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

The solution needs a way to encode a movie title so that it can be processed by our algorithm.  As the movie title could be of variable # words, these attributes can be included in the encoding: e.g. "Raiders of the Lost Ark" would be represented as 5 documents where each document is a word in the title. The title can also be assessed as a "Bag of Words".





## Data sources and AI methods
Data comes from opensource resources, such as Wikipedia:
https://en.wikipedia.org/wiki/Category:Lists_of_films_by_genre

## Challenges

Care needs to be taken that the training data is not so complete that it becomes a lookup exercise.  Also, accuracy may include a subjective element which may be included in the training/fitting phase of the process.

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

*The BuildingAI team at the University of Helsinki for producing an outstanding course with this and the Elements of AI course.
