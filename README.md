# Russell-FER
Code for facial expression recognition with vision-language model guidance and dynamic Russell-anchored emotion supervision.
# Learning Continuous Affective Semantics for Facial Expression Recognition via Large Vision-Language Model Guidance

This repository accompanies the manuscript:

> Yuke Xiang, Rui Fan, and Xiaoyu Tang, "Learning Continuous Affective Semantics for Facial Expression Recognition via Large Vision-Language Model Guidance," submitted to *Pattern Recognition Letters* (Manuscript ID: PRLETTERS-D-26-02250).

## Overview

This work introduces a facial expression recognition framework that connects affective judgments from a vision-language model with Russell's circumplex model of affect. Image-level emotion evidence is mapped into a valence-arousal space and used to construct continuous affective supervision for a lightweight recognition model. The proposed Dynamic Russell-anchored Emotion Loss balances affective alignment and categorical discrimination during training without requiring vision-language model inference at test time.

The method is evaluated on RAF-DB, FER+, and CK+.

## Repository Status

This repository has been created to support the reproducibility of the manuscript. The source code and experiment configurations are currently being organized and documented. They are not yet available in this repository.

The planned release will include:

- training and evaluation scripts;
- the Dynamic Russell-anchored Emotion Loss implementation;
- model and experiment configuration files;
- random-seed and reproducibility settings;
- data-preparation instructions;
- commands for reproducing the principal experiments; and
- scripts for generating the reported tables and visualizations.

The code will be released after the materials have been checked for completeness, documentation quality, and compliance with the licenses of the datasets and third-party components.

## Datasets

The experiments use the following publicly available facial expression recognition datasets:

- RAF-DB
- FER+
- CK+

The datasets are not redistributed through this repository. Users must obtain them from their official sources and comply with their respective licenses and terms of use.

## Reproducibility

The public release will document the software environment, preprocessing procedure, training configuration, and evaluation protocol. It will also include the random seeds used for the repeated experiments and the scripts used to calculate summary statistics and confidence intervals.

## Citation

Citation information will be added if the manuscript is accepted and the final bibliographic record becomes available.

## License

A source-code license will be added when the implementation is released. Dataset licenses are determined by the respective dataset owners.

## Contact

For questions about the manuscript, please contact the corresponding author:

Xiaoyu Tang  
School of Data Science and Engineering, South China Normal University  
Email: tangxy@scnu.edu.cn
