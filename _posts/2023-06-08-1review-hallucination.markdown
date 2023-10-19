---
layout: post
title:  "Uncertainty Aware Review Hallucination (Findings of ACL, 2021)"
date:   2023-06-08 18:25:00 +0200
categories: Research
---

From the abstract of my paper [*Uncertainty Aware Review Hallucination for Science Article Classification*](https://aclanthology.org/2021.findings-acl.443/):

> The high subjectivity and costs inherent in peer reviewing have recently motivated the preliminary design of machine learning-based acceptance decision methods. However, such approaches are limited in that they: a) do not explore the usage of both the reviewer and area chair recommendations, b) do not explicitly model subjectivity on a per submission basis, and c) are not applicable in realistic settings, by assuming that review texts are available at test time, when these are exactly the inputs that should be considered to be missing in this application. We propose to utilise methods that model the aleatory uncertainty of the submissions, while also exploring different loss importance interpolations between area chair and reviewers’ recommendations. We also propose a modality hallucination approach to impute review representations at test time, providing the first realistic evaluation framework for this challenging task.