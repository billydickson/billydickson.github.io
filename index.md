---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
![prof](../assets/images/prof2.jpg){: width="20%" height="auto"}
![brrrr](../assets/images/brrrr.jpg){: width="250" height="auto"}

dicksonb [at] iu [dot] edu

Hi, I'm a PhD student in computer science at Indiana University working with [Zoran Tiganj](https://homes.luddy.indiana.edu/ztiganj/).

Research Interests:

 - attention, memory, long-context modeling, hybrid models, cognitive science

More Interests:

 - llm training methodology, architecture, open models, distributed training, retrieval 
 - prepretraining, pretraining, postprepreposttraining, mid-training

Previously: 

I did a master's in computational linguistics at Indiana University with [Damir Cavar](https://damir.cavar.me/) in the [NLP Lab](https://nlp-lab.org/) working on time and event reasoning, and applied NLP with knowledge graphs and ontologies, and before that did my bachelor's at Michigan State University where I studied linguistics, TESOL, Chinese, and Korean, and did a summer language program at Harbin Institute of Technology.

---


Research:

**Gradual Forgetting: Logarithmic Compression for Extending Transformer Context Windows** \[paper\] Dickson, B., & Tiganj, Z. (in press). Gradual forgetting: Logarithmic compression for extending transformer context windows. In First Workshop on CogInterp: Interpreting Cognition in Deep Learning Models (NeurIPS 2025). 

> Most approaches to long-context processing increase the complexity of the transformer’s internal architecture by integrating mechanisms such as recurrence or auxiliary memory modules. In this work, we introduce an alternative approach that modifies the input representation itself, rather than the transformer architecture. Inspired by cognitive models of human memory, our method applies a scale-invariant logarithmic compression to the input tokens. The resulting compressed representation is processed by a standard, unmodified transformer, preserving architectural simplicity and avoiding state dependencies that complicate training. We evaluate this approach on the WikiText-103 and PG-19 language modeling benchmarks, showing a reduction in perplexity compared to uncompressed baselines. Moreover, performance improves consistently with longer compressed temporal contexts, highlighting input transformation as a simple yet effective technique for equipping transformers with long-range memory capabilities.

**Time-Local Transformer** [[paper]](https://link.springer.com/article/10.1007/s42113-025-00253-9)[[code]](https://github.com/cogneuroai/time-local-transformer) Dickson, B., Mochizuki-Freeman, J., Kabir, M.R., Tiganj, Z. Time-Local Transformer. Comput Brain Behav (2025). https://doi.org/10.1007/s42113-025-00253-9

> Human language processing, characterized by its ability to capture long-range dependencies in sequential inputs, operates under the constraints of limited working memory. In contrast, state-of-the-art transformer models in artificial intelligence rely on access to the fixed context window, which deviates from the dynamic nature of human cognition. Here, we propose a novel approach to reconcile this disparity by integrating a computational model of working memory into the transformer architecture. This biologically-inspired modification constructs a time-local transformer, capable of learning complex dependencies without needing the full input history. Our findings demonstrate that this approach still preserves the capacity of transformers for effective sequence processing. This work is a step towards developing AI models that align more closely with the principles of human brain function, opening new avenues for understanding the neural underpinnings of language and cognition.

**Comparing Perceptual Judgments in Large Multimodal Models and Humans** [[paper]](https://link.springer.com/article/10.3758/s13428-025-02728-w)[[code]](https://github.com/cogneuroai/multimodal-models-rock)[[website]](https://cognlp.com) Dickson, B., Maini, S. S., Sanders, C., Nosofsky, R., & Tiganj, Z. Comparing Perceptual Judgments in Large Multimodal Models and Humans. Behavior Research Methods 57, 203 (2025). https://doi.org/10.3758/s13428-025-02728-w

> Cognitive scientists commonly collect participants' judgments regarding perceptual characteristics of stimuli to develop and evaluate models of attention, memory, learning, and decision-making. For instance, to model human responses in tasks of category learning and item recognition, researchers often collect perceptual judgments of images in order to embed the images in multidimensional feature spaces. This process is time-consuming and costly. Recent advancements in large multimodal models (LMMs) provide a potential alternative because such models can respond to prompts that include both text and images and could potentially replace human participants. To test whether the available LMMs can indeed be useful for this purpose, we evaluated their judgments on a dataset consisting of rock images that has been widely used by cognitive scientists. The dataset includes human perceptual judgments along 10 dimensions considered important for classifying rock images. Among the LMMs that we investigated, GPT-4o exhibited the strongest positive correlation with human responses and demonstrated promising alignment with the mean ratings from human participants, particularly for elementary dimensions such as lightness, chromaticity, shininess, and fine/coarse grain texture. However, its correlations with human ratings were lower for more abstract and rock-specific emergent dimensions such as organization and pegmatitic structure. Although there is room for further improvement, the model already appears to be approaching the level of consensus observed across human groups for the perceptual features examined here. Our study provides a benchmark for evaluating future LMMs on human perceptual judgment data.


---

More Research:

**Advancing Adverse Drug Event Detection in Social Media Through Knowledge Graph and GraphRAG LLM Architectures** [[poster]](../assets/ade.pdf) Davis, A., Dickson, B., Cavar, D., Valdez, D., & Tyers, F. (2025). Advancing Adverse Drug Event Detection in Social Media Through Knowledge Graph and GraphRAG LLM Architectures [Poster presentation]. American Academy of Health Behavior (AAHB), San Diego, CA, United States.

**A Two-Stage NLP System for Extracting and Normalizing Adverse Drug Events from Tweets.** [[paper]](https://aclanthology.org/2024.smm4h-1.27.pdf) Davis, A., Dickson, B., & Kubler, S. (2024). A Two-Stage NLP System for Extracting and Normalizing Adverse Drug Events from Tweets. In Proceedings of the 9th Social Media Mining for Health Research and Applications (SMM4H 2024) Workshop and Shared Tasks, pages 117–120, Bangkok, Thailand. Association for Computational Linguistics. 

**Computing Ellipsis Constructions: Comparing Classical NLP and LLM Approaches** [[paper]](https://openpublishing.library.umass.edu/scil/article/id/2147/) Cavar, D., Tiganj, Z., Mompelat, L. V., & Dickson, B. Computing Ellipsis Constructions: Comparing Classical NLP and LLM Approaches. Society for Computation in Linguistics 7(1), 217–226 (2024). https://doi.org/10.7275/scil.2147

**Event sequencing annotation with TIE-ML** [[paper]](https://aclanthology.org/2022.isa-1.5/) Cavar, D., Aljubailan, A., Mompelat, L., Won, Y., Dickson, B., Fort, M., Davis, A., & Kim, S. (2022). Event sequencing annotation with TIE-ML. In Proceedings of the 18th Joint ACL - ISO Workshop on Interoperable Semantic Annotation within LREC2022 (pp. 33–41). Marseille, France: European Language Resources Association.

**Temporal Information and Event Markup Language: TIE-ML Markup Process and Schema Version 1.0** [[paper]](https://www.thinkmind.org/index.php?view=article&articleid=semapro_2021_1_60_30029) Cavar, D., Dickson, B., Aljubailan, A., & Kim, S. (2021). Temporal Information and Event Markup Language: TIE-ML Markup Process and Schema Version 1.0. In Proceedings of the 15th International Conference on Advances in Semantic Processing (SEMAPRO 2021), pages 29-36, Barcelona, Spain.

---

More More Interests:

 - video games, card games, racket sports, formula 1, indycar, gt racing, weightlifting, gojo 

--- 


Teaching:

Fall 2025, Assistant Instructor, Applied Machine Learning (Indiana University)

Summer 2024, [Generative AI and Symbolic Knowledge Representations: Large Language Models, Knowledge, and Reasoning](https://damir.cavar.me/ESSLLI24_LLM_KG.github.io/) (ESSLLI 2024, Leuven, Belgium)

Spring 2022, Fall 2023, Spring 2024, Fall 2024, Spring 2025, Assistant Instructor, Data Mining (Indiana University)

Spring 2020, Adult Communicative Focused English (Michigan State University)

---


Education:

PhD, Computer Science, Cognitive Science, Indiana University, ~2027


MS, Computer Science, Indiana University, 2025


MS, Computational Linguistics, Indiana University, 2022


BA, Linguistics, Michigan State University, 2020
