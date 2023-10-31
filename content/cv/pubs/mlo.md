---
title: "# Hunting for naval mines with deep neural networks"
date: 2023-03-10
tags:
- publication
---
Daniel Gebhardt, Keyur Parikh, Iryna Dzieciuch, Michael Walton, Nhut Anh Vo Hoang

![[cv/pubs/images/mlo.png]]

Explosive naval mines pose a threat to ocean and sea faring vessels, both military and civilian. This work applies deep neural network (DNN) methods to the problem of detecting minelike objects (MLO) on the seafloor in side-scan sonar imagery. We explored how the DNN depth, memory requirements, calculation requirements, and training data distribution affect detection efficacy. A visualization technique (class activation map) was incorporated that aids a user in interpreting the model's behavior. We found that modest DNN model sizes yielded better accuracy (98%) than very simple DNN models (93%) and a support vector machine (78%). The largest DNN models achieved <;1% efficacy increase at a cost of a 17x increase of trainable parameter count and computation requirements. In contrast to DNNs popularized for many-class image recognition tasks, the models for this task require far fewer computational resources (0.3% of parameters), and are suitable for embedded use within an autonomous unmanned underwater vehicle.