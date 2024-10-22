---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, my name is Cyril Chhun and this is my academic website. I am currently a PhD candidate at Télécom Paris, studying Automatic Story Generation and Evaluation. The title of my thesis is "Meta-Evaluation Methodology and Benchmark for Automatic Story Generation".

## Abstract of my PhD Thesis

Storytelling is a central component of human culture. Multiple approaches have been proposed to explore computational storytelling, despite the inherent challenges posed by the tasks of generating stories and assessing their quality. In this thesis, we design a meta-evaluation methodology and benchmark for Automatic Story Generation (ASG).

First, we lay the groundwork for conducting our meta-evaluation: we describe our chosen setting, provide definitions for the ASG and Automatic Story Evaluation (ASE) tasks, and propose an original set of six criteria for story evaluation.

Then, we introduce [HANNA](portfolio/hanna-benchmark/), our corpus of Human ANnotated NArratives, which contains 1,056 stories annotated w.r.t. our six criteria, and show that those criteria allow for a standardized human evaluation. We use Large Language Models (LLMs) to augment HANNA with 480 new stories and 150k+ rating annotations. We observe that LLMs obtain better grades than humans, as rated by selected LLMs.

After that, we perform our meta-evaluation benchmark on HANNA. We mainly observe that specific measures for ASE are needed, and that commonly-used measures (e.g. BLEU) are sub-optimal. We then show our analysis of LLM performance at ASE: we find that LLMs are currently the best proxy for human evaluation of ASG and that, in our specific setting, providing detailed guidelines does not improve correlations between LLM and human ratings.

Those results prompt us to study whether the performance displayed by LLMs at ASE and ASG can be explained through different factors. We perform a three-part study on LLM-generated explanations, and an analysis of pretraining data on LLM performance. Notably, we find that LLMs struggle to explain their answers with substantiated claims.
    
Finally, we outline three main research perspectives: designing specific ASE measures, further investigating LLM performance at ASG and ASE, and assessing and mitigating the impact of LLMs on society.
