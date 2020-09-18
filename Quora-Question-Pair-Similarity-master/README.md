
## Business Problem 
Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.
## Problem Statement

- Identify which questions asked on Quora are duplicates of questions that have already been asked.
- This could be useful to instantly provide answers to questions that have already been answered.
- We are tasked with predicting whether a pair of questions are duplicates or not.
## Data Source
- Source: https://www.kaggle.com/c/quora-question-pairs 

__Useful Links__
- Discussions: https://www.kaggle.com/anokas/data-analysis-xgboost-starter-0-35460-lb/comments


## Real world/Business Objectives and Constraints
- The cost of a mis-classification can be very high.
- You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.
- No strict latency concerns.
- Interpretability is partially important.

## Performance Metric
__Metric(s):__

- log-loss : https://www.kaggle.com/wiki/LogarithmicLoss<br>
- Binary Confusion Matrix

## How to run the file
First download the data from Data Source then run the file: QuoraQuesPairSim.ipynb.

## Authors
- Rahul Kumar - Complete work
