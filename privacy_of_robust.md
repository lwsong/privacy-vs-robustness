---
layout: page
title: "Privacy-robustness trade-offs"
---

# Privacy Risks of Securing Machine Learning Models against Adversarial Examples

**Useful Links**:  [Paper](http://www.princeton.edu/~pmittal/publications/security-vs-privacy-ccs19.pdf),  [Code](https://github.com/inspire-group/privacy-vs-robustness)

**Overview**  
Research into challenges of machine learning models typically considers the security domain and the privacy domain separately. It is thus unclear whether the defenses in one domain will have any unexpected impact on the other domain. In this paper, we combine the two domains by measuring the success of membership inference attacks (privacy domain) against defense methods that mitigate the threat of adversarial examples (security domain).

Membership inference attacks determine whether a data point is from the target model’s training set or not, reflecting the
information leakage of the model about its training data. 
Adversarial defense methods enhance model robustness against adversarial examples by ensuring that model predictions remain unchanged for a small around each (training) point.

Our evaluation results demonstrate that adversarial defense methods increase the model's generalization error and its sensitivity with regard to training data, thus make the model more vulnerable to membership inference attacks.
Our paper indicates a potential conflict between privacy and robustness (against adversarial examples) in machine learning.


**Authors**  
Liwei Song (Princeton University); Reza Shokri (National University of Singapore); Prateek Mittal (Princeton University)
