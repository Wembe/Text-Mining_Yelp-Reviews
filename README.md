# Text-Mining_Yelp-Reviews
INTRODUCTION

Yelp is a platform by which users can review businesses by leaving a rating and a text-based review.
While not all the reviews are made easily accessible by Yelp itself, the company does release a very large
compilation for the Yelp Dataset Challenge. The challenge is strictly for academic usage and is in its
thirteenth “round”. Students are invited to join the challenge for the chance to win one of ten awards of
$5,000.
Starbucks is one of the most popular coffeeshop chains in the United States. The chain, established in
Seattle in 1971, operates tens of thousands of individual locations around the world. The chain offers
the unique characteristic that consumers either expect to be quickly served and leave in a hurry, or they
expect a cozy atmosphere, wherein they will spend a few hours on a laptop doing work. Starbucks is a
popular chain, that has tremendous exposure on Yelp, and it was an excellent choice to explore and
analyze the reviews with popular text mining and machine learning strategies. Two primary business
questions were addressed – 1) does sentiment seem to show any predictive strength when evaluating
star rating? and 2) Can star rating being predicting using machine learning on its corresponding text
review?


RESULTS/RECOMMENDATIONS

Sentiment did show some correlation with ratings, but the ranges were so large and vocabulary so variable that it was not a strong indicator of rating score (sometimes people use good language when giving a poor review, and visa versa). 
Multinormial Naive Bayes algorithm was the best at predicting 1-star reviews (88% accuracy). 
Bernoulli Naive Bayes performed the best on the extremes (80% accuracy at ratings 1star and 5star) which are the most insightful for businesses. Recommended model for business use.
