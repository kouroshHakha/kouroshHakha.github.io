---
layout:     post
title:      "BagNet: Berkeley Analog Generator with Layout Optimizer Boosted with Deep Neural Networks"
date:       2019-12-28 12:00:00
arxiv:      https://arxiv.org/abs/1907.10515
authors:    Kourosh Hakhamaneshi, Nick Werblun, Pieter Abbeel, Vladimir Stojanovic 
event:      ICCAD 2019
blog:       https://bair.berkeley.edu/blog/2019/09/26/circuits/
github:     https://github.com/kouroshHakha/bag_deep_ckt/tree/kourosh
---
The discrepancy between post-layout and schematic simulation results continues to widen in analog 
design due in part to the domination of layout parasitics. This paradigm shift is forcing designers 
to adopt design methodologies that seamlessly integrate layout effects into the standard design 
flow. Hence, any simulation-based optimization framework should take into account time-consuming 
post-layout simulation results. This work presents a learning framework that learns to reduce the
number of simulations of evolutionary-based combinatorial optimizers, using a DNN that 
discriminates against generated samples, before running simulations. Using this approach, 
the discriminator achieves at least two orders of magnitude improvement on sample efficiency for 
several large circuit examplses including an optical link receiver layout.