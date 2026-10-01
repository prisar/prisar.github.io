---
layout: post
title:  "DPO improvements"
date:   2026-10-01 00:00:00 +0000
---


After weeks of waiting for better data it now seems that we have gotten some success in DPO training. So far the SFT results were good and DPO always 
under performed. After dozens of training runs which includes hours of training loops DPO seems to be catching up. Still there are lot to refine.
I believe we have a got to a point where we can confidently work on RL environment and make things bigger. The current version of RL environment is 
based on user simulator with personas like direct, vague, impatient. Along with user sim, we have rewards step, presentation credit, and terminal as final 
completion of the task.

The rollout is the runner. It alternates user personas with episodes and does things like accumulates the step reward, detects outcome from tool trace. 
It also computes the terminal reward.



<img width="508" height="610" alt="Screenshot 2026-10-01 at 6 28 56 PM" src="https://github.com/user-attachments/assets/76ad5cc6-efe7-48fc-9a46-f8469551dbf1" />
