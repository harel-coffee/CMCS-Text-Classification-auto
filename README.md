# CMCS-Text-Classification

This repository contains code for paper [Adapter-based fine-tuning of pre-trained multilingual language models for code-mixed and code-switched text classification](https://rdcu.be/cQSfa).

## Abstract of the paper

Code-mixing and code-switching are frequent features in online conversations. Classification of such text is challenging if one of the languages is low-resourced. Fine-tuning pre-trained multilingual language models is a promising avenue for code-mixed text classification. In this paper, we explore adapter-based fine-tuning of PMLMs for CMCS text classification. We introduce sequential and parallel stacking of adapters, continuous fine-tuning of adapters, and training adapters without freezing the original model as novel techniques with respect to single-task CMCS text classification. We also present a newly annotated dataset for the classification of Sinhala–English code-mixed and code-switched text data, where Sinhala is a low-resourced language. Our dataset of 10000 user comments has been manually annotated for five classification tasks: sentiment analysis, humor detection, hate speech detection, language identification, and aspect identification, thus making it the first publicly available Sinhala–English CMCS dataset with the largest number of task annotation types. In addition to this dataset, we also tested our proposed techniques on Kannada–English and Hindi–English datasets. These experiments confirm that our adapter-based PMLM fine-tuning techniques outperform or are on par with the basic fine-tuning of PMLM models.

## Dataset

https://huggingface.co/datasets/NLPC-UOM/Sinhala-English-Code-Mixed-Code-Switched-Dataset

## Authors

* [Himashi Rathnayake](https://github.com/HimashiRathnayake)
* [Janani Sumanapala](https://github.com/JananiSudeeptha)
* [Raveesha Rukshani](https://github.com/RaveeshaRukshani)
* [Dr Surangika Ranathunga](https://github.com/suralk)
