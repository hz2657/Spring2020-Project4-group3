# Project 4: Algorithm implementation and evaluation: Collaborative Filtering
![screenshot](figs/readme_image2.jpg)

### [Project Description](doc/project4_desc.md)

Term: Spring 2020

+ Team 3
+ Projec title: Algorithm implementation and evaluation: Collaborative Filtering
+ Team members
	+ Bian, Xinyi xb2154@columbia.edu
	+ Feng, Kangli kf2616@columbia.edu
	+ Shi, Mengying ms5922@columbia.edu
	+ Zhang, Ziyang zz2683@columbia.edu
	+ Zhu, Huizhe hz2657@columbia.edu
	
**Project summary:** 

In this project, we explored matrix factorization methods for recommender system. The goal is to recommend consumers with most appropriate products. Matrix factorization methods characterize both items and users by vectors of factors inferred from item rating patterns. High correspondence between item and user factors leads to a recommendation. Matrix factorization generally has 3 parts: 1. factorization algorithm  2. regularization  3. postpocessing. 

Given data sets including 610 users and 9724 movies, we implemented ALS withour regularizations and ALS with regularizations(R1 and R2).After fitting the model, we used Kernel Ridge Regreesion for postprocessing. Our result shows that the more latent factors we use, the lower the final RMSE is. 
![evaluationvisualization](figs/eval1.jpg)

	
**Contribution statement**: [default] All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

* Ziyang Zhang and Huizhe Zhu: implemented Altering Least Squares and postprocessing with Kernal Ridge Regression. 
* Mengying Shi and Xinyi Bian: implemented ALS with regularizations(R1 and R2)and postprocessing with Kernal Ridge Regression.
* Kangli Feng: Debug the code for RMSE and Presentations 


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
