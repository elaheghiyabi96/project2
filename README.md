# Modeling Tumor Escape Mechanisms for DC-Based Immunotherapy

This repository contains the code for simulating tumor growth and immune response in the context of DC-based immunotherapy. The project focuses on understanding the role of hypoxia and adenosine in tumor escape mechanisms and exploring the effectiveness of various therapeutic interventions.
##Abstract
The identification and control of tumor escape mechanisms are crucial in order to enhance the effectiveness of clinical treatment strategies for cancer patients. Experimental studies have revealed that tumor hypoxia and adenosine are two of such mechanisms. Additionally, research has demonstrated that hypoxia boosts the level of adenosine generated in the tumor microenvironment. Consequently, inhibiting both of these factors, in combination with conventional immunotherapeutic approaches like dendritic cell (DC)-based immunotherapy, can help to achieve a better clinical outcome. Nevertheless, this approach encounters challenges such as the requirement for many tests to understand the dynamics, determining the optimal dosages of these vaccines, as well as the appropriate timing of vaccination. However, mathematical models can assist us address these challenges. For the first time, in this study, mathematical tools including agent-based models, diffusion equations, and ordinary differential equations are utilized to model the escape mechanisms that hypoxia and adenosine provide for tumors in DC-based immunotherapy. Once the model is constructed and the parameters are estimated using experimental data, an optimal vaccination protocol is identified by adjusting the dose and timing of vaccination to minimize tumor growth. The model's sensitivity analysis revealed a significant impact of adenosine on the effectiveness of immunotherapy. The suppressive role of adenosine was found to be a major hindrance to successful treatment outcomes. However, inhibiting adenosine can potentially improve the performance of immunotherapy, according to the model's findings. The findings of this study provide valuable insights into the mechanisms underlying tumor escape conditions facilitated by hypoxia and adenosine, as well as their interaction with tumor immunotherapy. Additionally, an identifiability analysis was performed, which revealed that all model parameters are identifiable and can be accurately determined using experimental data. To sum up, the study contributes to a better understanding of the interplay between hypoxia, adenosine, and tumor immunotherapy, and can help guide the development of more effective treatments.
## Overview

The code in this repository simulates tumor growth in a spatial and temporal manner, incorporating immune cells and therapeutic vaccines targeting hypoxia and adenosine. Specifically, the project models the behavior of dendritic cells (DC) and evaluates the impact of immune-based therapies on tumor progression.
##Usage
Clone or download this repository.
Open MATLAB and navigate to the project directory.
Run the sirnaandpxandDc.m script to execute the tumor growth simulation.