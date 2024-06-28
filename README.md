# STGC
Solving Token Gradient Conflict in Mixture-of-Experts for Large Vision-Language Model

This is the code for "Solving Token Gradient Conflict in Mixture-of-Experts for Large Vision-Language Model".

A limitation of this work is that this performance increase brought by the proposed strategy is not sufficient enough now. The possible reason is that our method needs to assume that there exists conflicts in training data. However, the used 665k data now has not enough diversity. In addition, the 665k data is significantly fewer than the training data of the Large Language Model, so the tuning is only the stimulation for Large Language Model. The Large Language Model do not learn, but only adapt to vision, so it is not so effective for the better learning strategy of the MoE in Large Language Model. We can observe the more significant performance increase on the big private dataset in the company. Due to the computer resource constraints, we plan to expand the used public dataset size for more experiments in the next weeks. We will release the code when finishing all experiments.
