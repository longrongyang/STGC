# STGC
Solving Token Gradient Conflict in Mixture-of-Experts for Large Vision-Language Model
Longrong Yang, Dong Shen, Chaoxiang Cai, Fan Yang, Size Li, Di Zhang, Xi Li

This is the code for "Solving Token Gradient Conflict in Mixture-of-Experts for Large Vision-Language Model".

A main limitation of this work is that the performance increase brought by the proposed strategy is not sufficiently significant now. The possible reason is that our method needs to assume that there are severe conflicts in the training data. However, the 665k data we are using are not diverse enough. We have observed a more significant performance increase in the large private dataset within the company. Due to computer resource constraints, we plan to expand the size of the public dataset we are using for further experiments in the next few weeks. The code will be released after we finish all experiments.
