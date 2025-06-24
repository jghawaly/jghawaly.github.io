---
title: "Exploring Large Language Models for Semantic Analysis and Categorization of Android Malware"
collection: publications
permalink: /publication/2024-malparse-number-7
excerpt: 'In this paper, we explore leveraging Large Language Models (LLMs) for semantic malware analysis to expedite the analysis of known and novel samples. Built on GPT-4o-mini model, MalParse is designed to augment malware analysis for Android through a hierarchical-tiered summarization chain and strategic prompt engineering. '
date: 2024-12-12
venue: '2024 Annual Computer Security Applications Conference Workshops (ACSAC Workshops)'
paperurl: 'https://ieeexplore.ieee.org/document/10917287'
---

Abstract:

Malware analysis is a complex process of examining and evaluating malicious software’s functionality, origin, and potential impact. This arduous process typically involves dissecting the software to understand its components, infection vector, propagation mechanism, and payload. Over the years, deep reverse engineering of malware has become increasingly tedious, mainly due to modern malicious codebases’ fast evolution and sophistication. Essentially, analysts are tasked with identifying the elusive needle in the haystack within the complexities of zero-day malware, all while under tight time constraints. Thus, in this paper, we explore leveraging Large Language Models (LLMs) for semantic malware analysis to expedite the analysis of known and novel samples. Built on GPT-4o-mini model, MalParse is designed to augment malware analysis for Android through a hierarchical-tiered summarization chain and strategic prompt engineering. Additionally, MalParse performs malware categorization, distinguishing potential malware from benign applications, thereby saving time during the malware reverse engineering process. Despite not being fine-tuned for Android malware analysis, we demonstrate that through optimized and advanced prompt engineering MalParse can achieve up to 77% classification accuracy while providing highly robust summaries at functional, class, and package levels. In addition, leveraging the backward tracing of the summaries from package to function levels allowed us to pinpoint the precise code snippets responsible for malicious behavior.

Recommended citation:
B. J. Walton, M. E. Khatun, J. M. Ghawaly and A. Ali-Gombe, "Exploring Large Language Models for Semantic Analysis and Categorization of Android Malware," 2024 Annual Computer Security Applications Conference Workshops (ACSAC Workshops), Honolulu, HI, USA, 2024, pp. 248-254, doi: 10.1109/ACSACW65225.2024.00035.
