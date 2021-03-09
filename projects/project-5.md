---
layout: project
type: project
image: images/covid.jpg
title: Experimentation of adversarial pertubation attack on COVID-19 Detection attack
permalink: projects/Coivd-19
# All dates must be YYYY-MM-DD format!
date: 2019-09-25
labels:
  - EasyEDA
  - esp8266
  - PCB design
  - C++

summary: This project is about the vanuarability of machine learning based covid detection andexploiting the vanuarability
---

<div class="ui images">
  <img class="ui image" src="../images/covid_wall.jpg">
</div>


Under the epidemic of the novel coronavirus disease 2019 (COVID-19), chest X-ray computed tomography imaging is being used for effectively screening COVID-19 patients. The 
development of computer-aided systems based on deep neural networks (DNNs) has been advanced, to rapidly and accurately detect COVID-19 cases, because the need for expert 
radiologists, who are limited in number, forms a bottleneck for the screening. However, so far, the vulnerability of DNN-based systems has been poorly evaluated, although DNNs are vulnerable to a single perturbation, called universal adversarial perturbation (UAP), which can induce DNN failure in most classification tasks.

Me and my team are  focused on representative DNN models for detecting COVID-19 cases from chest X-ray images and evaluate their vulnerability to UAPs generated using simple 
iterative algorithms. We consider nontargeted UAPs, which cause a task failure resulting in an input being assigned an incorrect label, and targeted UAPs, which cause the DNN to 
classify an input into a specific class. The results indicate that careful consideration is required in practical applications of DNNs to COVID-19 diagnosis; in particular, they 
emphasize the need for strategies to address security concerns. As an example, we show that iterative fine-tuning of the DNN models using UAPs improves the robustness of the DNN models against UAPs
