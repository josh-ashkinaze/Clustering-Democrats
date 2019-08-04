# Clustering Democrats

In this analysis, I use Normalized Google Distance to look at which Democrats we group together.  
The Normalized Google Distance (NGD) is a semantic similarity measure, calculated based on the number of hits returned by Google for a set of keywords. 
If keywords have many pages in common relative to their respective, independent frequencies, then these keywords are thought to be semantically similar. 
If two search terms w1 and w2 never occur together on the same web page, but do occur separately, the NGD between them is infinite. 
If both terms always occur together, their NGD is zero.

1. Which aspect of coffee is most important for assigning an overall rating?

2. Which countries receive overall ratings better than their component ratings would predict?

To answer these questions, I use exploratory analysis and a heteroskedasticity-robust fixed effect OLS model. 

My findings: 

1. The most important coffee qualities are flavor, aftertaste, and balance. These are the qualities that are most predictive of overall coffee rating.

2. Everyone should try Vietnmanese or Burundi coffee. Coffee from these two countries recieves an overall rating above what its component ratings would predict.


Read my blog for a write-up and look at the ipynb notebook for analysis! 

Blog entry: https://www.joshash.space/data-science/the-most-important-aspect-of-coffee


```
         .        .  
  * _  __|_  _. __|_ 
  |(_)_) [ )(_]_) [ )
._|

```
