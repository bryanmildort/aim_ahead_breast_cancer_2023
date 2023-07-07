# AIM-AHEAD Health Equity Data Challenge 2023
### by Bryan Mildort

This repository contains a Jupyter Notebook with the source code on training a [Vision Transformers model](https://huggingface.co/facebook/dino-vitb16) and classifying breast cancer stages from medical biopsy slide images provided during the [AIM-AHEAD Health Equity Data Challenge 2023](https://app.nightingalescience.org/contests/8lo46ovm2g1j).

Just open [breast_cancer_contest.ipynb](https://github.com/bryanmildort/aim_ahead_breast_cancer_2023/blob/main/breast_cancer_contest.ipynb) and run each cell within your environment from the home direcotry (/home/ngsci). You may also choose to run the commands individually in order.


The general schema of the methods is as follows:

Convert slide images (.ndpi files) into JPGs -> Preprocess Images and Initiate Transformers Model -> Evaluate on Holdout Set
