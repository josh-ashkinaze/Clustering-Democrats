# Clustering Democrats


In this analysis, I use [Normalized Google Distance (NGD)](https://github.com/josh-ashkinaze/Normalized-Google-Distance)
) to look at which Democrats we group together. 

[Read my blog](https://www.joshash.space/data-science/clusters-of-democratic-candidates-1) for a write-up, and look at the ipynb notebook for analysis! 


## My questions

1. Using Google search results, what are the clusters of Democratic candidates?

2. Which candidate is the most unique?


## My findings
### Finding 1 
There is a clear "frontrunner" cluster. This cluster (Stars) leads in the polls and is talked about together. And similarly, the group behind the frontrunners (Upstarts) in the polls is also talked about together. Of the Upstarts, Mayor Pete and Booker are the most connected to the Stars.

### Finding 2
Andrew Yang is the most unique candidate. He had the highest average NGD to other candidates. Yet if we had to place him in a cluster based on NGD, he is most similar to the Economic Pragmatist cluster.


## Files 
* ```ngd_democrats.py``` is a script to calculate the pairwise NGD for 24 candidates 
* ```candidate_analysis.ipynb``` is a Python notebook of analysis 


```
         .        .  
  * _  __|_  _. __|_ 
  |(_)_) [ )(_]_) [ )
._|

```
