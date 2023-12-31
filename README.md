# Predicting Tennis Match Outcomes

View this blog post about my analysis on [my personal site](https://kevinrosenfield.com/Predict-Tennis/)

I am in the process of writing a python script that uses logistic regression to predict the outcomes of professional tennis matches on the basis of each players' previous match performance. The first iteration will only take into account each player's most recent match, but subsequent attempts to improve the model's predictive power will use more complex feature combinations, take momentum over multiple matches into account, and factor in the head-to-head record and statistics of each player.

I also hope to find richer data sources to incorporate into future iterations, as the data for which a large enough sample to run an adequately powered machine learning algorithm only covers the most superficial match statistics. I hope to train an initial model that can predict outcomes at least better than chance (50%), but would like to reach a much higher number.

A truly great model would correctly predict upsets more than 50% of the time. An upset occurs when the lower ranked player wins the match. In more prominent tournaments, seeded players defeat their unseeded opponents most of the time. Predicting upsets at this level would be a real measure of success.

Figure 1. Distribution of ranks among match winners and losers.
<img src="/images/tennis_ranks.png" style="max-width:565px">

This post is a work in progress!

-Kevin