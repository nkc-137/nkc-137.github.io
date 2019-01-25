---
layout: post
title: "American Express Analyze This 2018 competition"
date: 2019-01-25
---

# Competition

Amex Analyze This is a data science competition held by American Express across all the Indian Institute of Technology Institutes across India.

I had participated in this competition in 2017 and being a newbie in Data Science at that time my performance was very poor, nonetheless, it was a good learning experience for me.

After taking up a bunch of courses and practicing on online datasets I participated in Amex Analyze This in 2018 and this time the result was satisfactory.

I teamed up with my friend from IIT Madras and we had a nail-biting experience participating in the competition. The competition went on for 6 days, we had to constantly work on the dataset and try to stay up on the leaderboard, we also had to validate our model on the evaluation dataset and finally we also had to submit a presentation explaining our solution; each of these carried weightage in the final score. Those 6 days were a roller-coaster ride, requiring us to dedicate all the whole day to keep ourselves floating in the leaderboard. At the end of the competition we were 12th of the leaderboard. The whole experience culminated in our team being one of the two teams in my campus to be offered a Pre-Placement Interview (PPI).

The problem statement for the competition was to predict which customer was most likely to be a  defaulter based on features provided in the dataset. We were given a budget and there was a penalization for every false negative value we get in the leaderboard dataset. For the leaderboard score, points from leaderboard dataset were considered until the budget is maxed out.

Coming to the solution that worked for us, we had a try a lot of different approaches and models to arrive at the solution that worked well. In this blog I will discuss the whole pipeline that we developed in order get a good accuracy.

Below is a schematic of the pipeline:

<p align="center">
<img src="/home/kapil/nkc-137.github.io/assets/Amex.jpg">
</p>
