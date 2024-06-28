# STGC
Solving Token Gradient Conflict in Mixture-of-Experts for Large Vision-Language Model

This is the code for "Solving Token Gradient Conflict in Mixture-of-Experts for Large Vision-Language Model".

A main limitation of this work is that the performance increase brought by the proposed strategy is not sufficiently significant now. The possible reason is that our method needs to assume that there are severe conflicts in the training data. However, the 665k data we are using are not diverse enough. In addition, the 665k tuning data are significantly fewer than the training data of Large Language Models, so the tuning may be merely stimulating the existing knowledge in Large Language Models. In other words, Large Language Models do not learn new information but only adapts to visual data, which may render the proposed strategy (designed for the MoE in Large Language Models) ineffective. We have observed a more significant performance increase in the large private dataset within the company. Due to computer resource constraints, we plan to expand the size of the public dataset we are using for further experiments in the next few weeks.
