---
layout:     post
title:      "Skill Preferences: Learning to Extract and Execute Robotic Skills from Human Feedback"
date:       2021-30-31 20:14:00
arxiv:      https://arxiv.org/abs/2108.05382
authors:    Xiaofei Wang, Kimin Lee, **Kourosh Hakhamaneshi**, PieterAbbeel, Michael Laskin
event:      Preprint
<!-- blo g:       https://bair.berkeley.edu/blog/2019/09/26/circuits/ -->
<!-- github:     https://github.com/kouroshHakha/bag_deep_ckt/tree/kourosh -->
---
A promising approach to solving challenging long-horizon tasks has been to extract behavior priors (skills) by fitting generative models to large offline datasets of demonstrations. However, such generative models inherit the biases of the underlying data and result in poor and unusable skills when trained on imperfect demonstration data. To better align skill extraction with human intent we present Skill Preferences (SkiP), an algorithm that learns a model over human preferences and uses it to extract human-aligned skills from offline data. After extracting human-preferred skills, SkiP also utilizes human feedback to solve down-stream tasks with RL. We show that SkiP enables a simulated kitchen robot to solve complex multi-step manipulation tasks and substantially outperforms prior leading RL algorithms with human preferences as well as leading skill extraction algorithms without human preferences.