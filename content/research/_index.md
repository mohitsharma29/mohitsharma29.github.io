---
title: "Research Statement"
date: 2025-05-27
hidemeta: true
description: "Detailed Research Interests"
---
<img src="research_statement_cover.png" width="600" height="350" alt="Generated using ChatGPT: Generate an image of a Phd student trying to work on machine learning theory and also trying to work on empirical machine learning, while appearing totally overwhelmed." style="display: block; margin: 0 auto">
<!-- ![Generated using ChatGPT: Generate an image of a Phd student trying to work on machine learning theory and also trying to work on empirical machine learning, while appearing totally overwhelmed.](research_statement_cover.png) -->
<br>
<br>

<p text-align='justify'>

My training so far has been around imperfect data. My PhD started with trying to understand how pretraining helps model performance downstream, even if the pretraining is done on extremely noisy, sparse labels ([arXiv](https://arxiv.org/pdf/2110.06827)). This was when Self-Supervised Learning methods started becoming mainstream and showed immense promise. 

Towards the end of that project, I felt the need to get into more mathematics of ML. At the same time, we were short on computing resources, and working more on pretraining always felt like a waiting game. Hence, around this time, I decided to look into Fairness in Machine Learning. At that time and even now, Fair ML offers a plethora of open problems with significant implications for Machine Learning. Our previously published [paper](https://proceedings.mlr.press/v235/sharma24a.html) tackles exactly this: when is it true that imposing fairness on your model amounts to obtaining the most accurate classifier, especially when the data is imperfect. Around this time, I started to get interested in [Bayes optimality](https://en.wikipedia.org/wiki/Bayes_classifier) (the best model for a given data distribution).

In the real world, our data will never be free of noise and spurious correlations of the past. Hence, there needs to be some assurance and guarantee that the models we train on such noisy and biased data will get the job done and comply with safety and regulatory guidelines. Therefore, my research currently studies many such scenarios from the perspective of what's theoretically possible (Bayes Optimality). I am also working on generaling to other imperfect data settings, especially those requiring cost-sensitive learning where your errors can have unequal weights. Fairness in ML is just one example of [this](https://proceedings.mlr.press/v81/menon18a.html), where the weights should be different between data groups to satisfy a given fairness constraint. 

On a more philosophical level, my long-term aim is to connect theory and practice. Machine learning has had incredible empirical success while posing some of the most complex theory questions one can encounter. I like to believe in the hypothesis that theory and practice can help each other (especially in the current climate where the consensus is to ignore theory completely) and that Machine Learning can benefit greatly from rigorous analysis, even in the age of LLMs. However, at the same time, there seems to be a disconnect between what the theory community tackles and what the empirical community wants and works on. This gap has only massively increased recently with the advent of pretrained, massive models. Therefore, I want to operate at a junction between these two communities. If nothing, the theory community can almost surely help everyone come up with reasonable and well-justified heuristics and guidelines to train and use Machine learning models.
</p>