---
title: "Research Statement"
date: 2025-05-27
hidemeta: true
description: "Detailed Research Interests"
---
<!-- <img src="research_statement_cover.png" width="600" height="350" alt="Generated using ChatGPT: Generate an image of a Phd student trying to work on machine learning theory and also trying to work on empirical machine learning, while appearing totally overwhelmed." style="display: block; margin: 0 auto">
<!-- ![Generated using ChatGPT: Generate an image of a Phd student trying to work on machine learning theory and also trying to work on empirical machine learning, while appearing totally overwhelmed.](research_statement_cover.png) -->

<p text-align='justify'>
<u><i> Past Experience</i></u>

My training so far has been around imperfect data. My PhD started with trying to understand how pretraining helps model performance downstream, even if the pretraining is done on extremely noisy, sparse labels ([arXiv](https://arxiv.org/pdf/2110.06827)). This was when Self-Supervised Learning methods started becoming mainstream and showed immense promise. 

Towards the end of that project, I decided to transition to more theoretical topics. Hence, around this time, I decided to look into Fairness in Machine Learning. At that time and even now, Fair ML offers a plethora of open problems with significant implications for Machine Learning. Our previously published [paper](https://proceedings.mlr.press/v235/sharma24a.html) at ICML 2024 tackles exactly this: when is it true that imposing fairness on your model amounts to obtaining the most accurate classifier, especially when the data is imperfect. The tools used in our paper can be leveraged to work for many cost-sensitive applications and label bias models. Around this time, I started to get interested in [Bayes optimality](https://en.wikipedia.org/wiki/Bayes_classifier) (the best model for a given data distribution).

In the real world, our data will never be free of noise and spurious correlations of the past. Hence, there needs to be some assurance and guarantee that the models we train on such noisy and biased data will get the job done and comply with safety and regulatory guidelines. Therefore, my research currently studies many such scenarios from the perspective of what's theoretically possible (Bayes Optimality). I am also working on generalizing to other imperfect data settings, especially those requiring cost-sensitive learning, where your errors can have unequal weights. Fairness in ML is just one example of [this](https://proceedings.mlr.press/v81/menon18a.html), where the weights should differ between data groups to satisfy a given fairness constraint. 

Building on our previous [work]((https://proceedings.mlr.press/v235/sharma24a.html)), we recently also studied whether we can steer a given data distribution towards an 'ideal' distribution, where there are no trade-offs between fairness and accuracy. To that end, in our recent work ([arXiv](https://arxiv.org/abs/2509.15759), [blog](https://open.substack.com/pub/mohitsharma17/p/seeking-ideal-data-distributions?r=1tjy9l&utm_campaign=post&utm_medium=web&showWelcomeOnShare=true)), which has been accepted for presentation and publication at Neurips 2025, we were able to study such conditions assuming a parametric distribution over our data. However, we also noticed that the most general steering condition will result in Non-Convex optimization programs. Therefore, we propose following an Affirmative Action for the underprivileged group to make the optimization tractable. Since there is some evidence that the internal representation of large models behaves according to some Gaussian, as a proof of concept, we were able to leverage our results to steer LLMs away from toxic generation and reduce bias in Multi-class classification over embeddings extracted from LLMs. We also hope that some of these ideas can be used for principled training of <i>Fair</i> Generative models.

<u><i>Current Projects</i></u>

Currently, I am on track to submit my thesis early next year. My last few projects involve exploring Bayes Error Estimation from soft labels (extension of ideas from [Ishida et al.](https://openreview.net/forum?id=FZdJQgy05rz)) and exploring the role of randomization in optimal fair classification (extension of ideas from [Agarwal et al.](https://arxiv.org/pdf/2406.03142)).

<!-- 
On a more philosophical level, my long-term aim is to connect theory and practice. Machine learning has had incredible empirical success while posing some of the most complex theory questions one can encounter. I like to believe in the hypothesis that theory and practice can help each other (especially in the current climate where the consensus is to ignore theory completely) and that Machine Learning can benefit greatly from rigorous analysis, even in the age of LLMs. However, at the same time, there seems to be a disconnect between what the theory community tackles and what the empirical community wants and works on. This gap has only massively increased recently with the advent of pretrained, massive models. Therefore, I want to operate at a junction between these two communities. If nothing, the theory community can almost surely help everyone come up with reasonable and well-justified heuristics and guidelines to train and use Machine learning models. -->

<!-- <u><i>Research Interests</i></u>

Over the course of my PhD, I have been fascinated by how rigourous statistics can help Machine Learning. If I could go back, I would anyday study and specialize in statistics. Going forward,  -->
</p>