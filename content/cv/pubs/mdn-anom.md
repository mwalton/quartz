---
title: "Unsupervised anomaly detection for digital radio frequency transmissions"
date: 2023-03-10
tags:
- publication
---
Michael Walton, Maurice Ayache, Logan Straatemeier, Daniel Gebhardt, Benjamin Migliori
![[cv/pubs/images/rf.png]]

We present a novel method of unsupervised anomaly detection using long-short-term memory mixture density networks (LSTM-MDN), applied to timeseries data of digital radio transmissions. The modern radio frequency (RF) environment is a dynamic and ever-changing complex milieu of signals, environmental effects, unintentional interference, and intentional jamming. A consequence of this complex mix is that RF receivers must become better and better at rejecting anomalous signals in order to recover the transmitted information. However, it is not always possible to know a priori what constitutes a valid signal and what constitutes an anomaly (intentional or otherwise), especially with the adoption of cognitive radio techniques. We show that an LSTM-MDN model is able to rapidly learn the training set and produce probability distribution functions for the expected signal as a function of time. We then demonstrate that the negative log likelihood of an incoming test transmission, conditioned on the training set, provides a metric that allows anomalous signals to be detected and labeled. We demonstrate this method for eight popular modulations and for three different anomaly types. By applying unsupervised learning in the temporal domain, we report a fully-generalizable anomaly detection method that may be applied to signals for which the transmission parameters may be unknown or obscured.