---
layout: post
title:  "Human preference prediction"
date:   2025-09-07 00:00:00 +0000
---

Many of the use cases for optimizing LLM performance involves human prediction. We will dive into how LLMs can be fine-tuned to predict human preference.

### Supervised Fine Tuning - SFT

In supervised fine tunining we use a base LLM and a dataset of human prefered responses. The idea is to train the LLM to predict the which LLM will be 
preffered.


### RLHF

In RLHF, the training is very hard to do. And due to stability reasons also, it is not useful in normal use cases. In bigger setup, it is normally used.


### DPO

DPO is one of the common method to optimize for human preference. Unlike RLHF it doesn't require a lot of resouces. It uses some cleaver tricks.
