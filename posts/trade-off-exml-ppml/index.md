<!--
.. title: Trade-offs between Privacy-Preserving and Explainable Machine Learning in Healthcare
.. slug: trade-off-exml-ppml
.. date: 2020-09-2 10:30:13 UTC+01:00
.. tags: AI, Paper, Learning, Tech
.. category: Tech
.. link: 
.. description: 
.. type: text
.. status: 
-->

In this seminar paper we conducted a literature research to investigate trade-offs between privacy preservig and explainable machine learning.
<!-- TEASER_END -->

Explainability and privacy are two key concerns when training a machine learning model,especially in critical information infrastructure, such as the healthcare sector.  So far,researchers are uncertain of possible trade-offs and their impact. We have conducted asystematic literature review to identify the current state of research and possible trade-offsbetween the explainability and privacy of machine learning models.

We present possible ways of implementing explainability methods in a privacy-preserving setting with feder-ated learning focused on the analysis of medical images. Our results show that only a fewresearchers have discussed possible trade-offs between explainable and privacy-preservingmachine learning. The relevant papers indicate that there is a natural trade-off. A higherlevel of explainability can make a model more vulnerable to attacks and therefore have ahigher risk of privacy leakage. 

For our federated learning example, we have selected three methods (SHapley Additive exPlanations, Gradient-weighted Class Activation Mapping,and Local Interpretable Model-Agnostic Explanations) that one can theoretically imple-ment without risking privacy. However, experiments would be necessary to confirm theseideas.

Read full seminar paper [here](/docs/AIFB_Seminararbeit-10.pdf)
