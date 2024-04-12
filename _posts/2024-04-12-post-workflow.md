---
layout: post
title: Share my current Raytune+mlflow workflow for model training
date: 2024-04-11 14:26:00-0400
description: First blog post!
tags: workflow
categories: workflow
giscus_comments: false
related_posts: false
related_publications:
---

When training a model, we would like to make sure we reached the its best performance with the most suitable combination of hyperparameters. Grid search can be enough for architectures with less variables to tune, but when you architecture is getting complex, this workflow can be definitely helpful to monitor everything.

Raytune is a part of Ray library,it has several common used hyperparameter searching algorithms to help your model to get the optimal performance. In the meantime, mlflow is a visualization tool to make graphs for every parameter you want to watch. It is good to have a GUI like mlflow to track every run when you are in a huge project with many experiments to check.

I would like to share my experience to select params for monitoring. Raytune usually has your validation accuracy/loss reported to represent the results. I also recommend you to add all the hyperparams you want to tune to trace the trend. Additionally, it is a good idea to add training loss to make sure you have the results of the training process.


**But**, one thing important to notice is that: The validation accuracy is not the actual generalizable accuracy!

You should always have a separated test set to run the final test and make sure the model can be generalized instead of tuning for only the validation set. This point is pretty tricky and also got me to believe that the validation accuracy is the final accuracy. I guess this kind of division could be even more essential when we do pre-train on a larger dataset.