---
title: Undergrad Final Project
summary: 'Evaluating Manipulative Language Taxonomies for Human and LLM-Based Classification of Political Advertisements'
year: 2026
tags: [Research]
image: /img/kings.png
link: https://github.com/jasminelx/Manipulative-Language-Detection
order: 2
---
There are several widely used taxonomies of manipulative language which provide the foundation for many studies that evaluate how well large language models classify manipulative content. My project shifted focus to the taxonomies themselves, examining how effectively they support both human annotation and automated classification.

I compared three established taxonomies: Noggle's taxonomy, Simon's taxonomy, and Information Manipulation Theory 2, using a dataset of 600 political advertisements sampled from the 2022 Meta and Google United States general election advertising dataset. Each taxonomy was evaluated through three approaches: human annotation, large language model annotation using zero shot and few shot prompting, and a set of taxonomy quality metrics including comprehensiveness, reliability, robustness, and conciseness.

The results highlighted clear differences between the taxonomies. Noggle's taxonomy was preferred by human annotators and achieved the highest comprehensiveness and inter annotator reliability, whilst IMT2 achieved the strongest agreement between large language models. Few shot prompting produced results that were very similar to zero shot prompting across all three taxonomies.

Overall, this project demonstrates that taxonomy choice has a substantial influence on both human and large language model classification. The findings show that selecting choice of taxonomy is an important variable when evaluating automated manipulation detection in political advertisements.
