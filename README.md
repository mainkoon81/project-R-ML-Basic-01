# R-project-ML-Basic

## Multivariate_Analysis / Machine Learning playground with R

### [Contents] 

__Lab-01.__ Association Rule Mining 
  - package: arules 
  - func:

__Lab-02.__ Clustering 
  - package: cluster, e1071, mclust 
  - func:

__Lab-03.__ Regression 
  - package: 
  - func:

__Lab-04.__ Classification 
  - package: MASS, nnet, ROCR, rpart, party, adabag, randomForest, 
  - func:

__Lab-05.__ Dimension Reduction 
  - package: Mass, vegan, 
  - func:
----------------------------------------------------------------------

<img src="https://user-images.githubusercontent.com/31917400/32491154-907d38fa-c3ad-11e7-95a2-7a5ce5588d81.jpg" />

#### >Lab-01. Association Rule Mining

__Data:__ The Data were collected recording votes in the Irish parliament (D´ailEireann), prior to the general election, in early 2016. Extra details of the votes can be found at (http://www.oireachtas.ie/parliament/) and the data are for the votes on January 14th-28th.

__Story:__ Association rule mining has a purpose to find frequent co-occurring relationships among a collections of independent items in the dataset so that we can predict the occurrance of next items. In this project, we aim to discover and investigate certain patterns or trends that might reside in their voting behaviour on diverse (23) propositions. Each column numbers in the dataset refers each different proposition put to those votes. And we tag each ‘YES-votes’, ‘NO-votes’, using those column numbers that reflect what propositions those voting choices correspond to. 

What we focus on, in the beginning, is to find association pattern that reveals interesting connections between ‘Yes-votes.’ This analysis is repeated between ‘No-votes’ as well. Given that the association patterns we are looking for are not subject to the causal and effect attributes in the dataset, it is not a bad idea to rely more on seeking co-occurrence relationships between items. Likewise, when it comes to the choice of quality measures as a threshold for rule mining, Support measure over Confidence or Lift seems to be the most convincing as Support, by definition, embodies the intersecting (co-occurrence) relationship between items. However, Lift measure also can be useful to verify reliability of the association rules that are generated by Support measure. For example, if a Lift-value is greater than 1, it represents a positive effect on the occurrence of one another. If a Lift-value is equal to 1, it means the occurrences of the item are independent each other. If a Lift-value is less than 1, it means the proposed occurrence has a probability less than 1.  

__Note:__ We need to get the data into an appropriate binary format (from Y's and N's to 1’s and 0’s) before analysis, then set it up in transaction format.




-------------------------------------------------------------------------------

<img src="https://user-images.githubusercontent.com/31917400/32504026-b28a518e-c3d6-11e7-93b6-9c8ad96a3d8a.jpg
" />

#### >Lab-03. Regression

__Data:__ 




