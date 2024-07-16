# On the Use of Large Language Models for Table Tasks

The proliferation of LLMs has catalyzed a diverse array of applications. This tutorial delves into the application of LLMs for tabular data and targets a variety of table-related tasks, such as table understanding, text-to-SQL conversion, and tabular data preprocessing. 

It surveys LLM solutions to these tasks in five classes, categorized by their underpinning techniques: prompting, fine-tuning, RAG, agents, and multimodal methods. It discusses how LLMs offer innovative ways to interpret, augment, query, and cleanse tabular data, featuring academic contributions and their practical use in the industrial sector. 

It emphasizes the versatility and effectiveness of LLMs in handling complex table tasks, showcasing their ability to improve data quality, enhance analytical capabilities, and facilitate more intuitive data interactions. By surveying different approaches, this tutorial highlights the strengths of LLMs in enriching table tasks with more accuracy and usability, setting a foundation for future research and application in data science and AI-driven analytics.

## Outline

1. Introduction [[slides]()]
- 1.1 Tabular data          
- 1.2 Table tasks
- 1.3 Benchmarks 
- 1.4 Summary of approaches prior to the rise of LLMs 
- 1.5 LLM preliminaries 
- 1.6 Key techniques for the use of LLMs in table tasks
2. Prompting [[slides]()]
- 2.1 Transformation of tabular data to prompts 
- 2.2 Prompting techniques 
- 2.3 Representative solutions and examples 
3. Fine-tuning [[slides]()]
- 3.1 Base model selection 
- 3.2 Data preparation 
- 3.3 Construction of instruction data 
- 3.4 Fine-tuning techniques 
- 3.5 Representative solutions and examples

  (Break)
  
4. Retrieval-augmented generation (RAG) [[slides]()]
- 4.1 Basic RAG techniques 
- 4.2 Advanced RAG techniques 
- 4.3 RAG for table tasks
- 4.4 Representative solutions and examples
5. LLM agents [[slides]()]
- 5.1 LLM agent preliminaries 
- 5.2 LLM agents for table tasks 
- 5.3 Representative solutions and examples 
6. Vision-language models (VLMs) [[slides]()]
- 6.1 VLM preliminaries 
- 6.2 Comparison of VLM and LLM methods for table tasks 
7. Conclusions [[slides]()]
- 7.1 Summary of state-of-the-art
- 7.2 Issues and future research directions
- 7.3 Societal impacts

## Presenters
**Yuyang Dong** is a Principal Researcher at NEC.He earned his Ph.D. degree from the University of Tsukuba in 2019. He specializes in tabular data searching and NLP, with his expertise in \textbf{tabular data processing} evidenced by publications in prestigious venues. Dong leads the project [[Jellyfish](https://huggingface.co/NECOUDBFM)], a leading-edge LLM for tabular data processing that has garnered thousands of monthly downloads on Hugging Face. He is a key contributor to NEC cotomi-core, a suite of robust, self-developed LLMs in both Japanese and English, underpinning NEC's Generative AI Service.

**Masafumi Oyamada** is the Chief Scientist and Director of Generative AI Foundations Research at NEC. He was awarded his Ph.D. degree from the University of Tsukuba in 2018. At NEC, he spearheads research and development efforts in the domain of LLMs, including the creation of cotomi-core, a series of high-performance and efficient LLMs. His interdisciplinary work has bridged the gap between tabular data and machine learning. 

**Chuan Xiao** is an Associate Professor at Osaka University and a Guest Associate Professor at Nagoya University. He completed his Ph.D. at the University of New South Wales in 2010. His research interests span data preprocessing, computational social science, and NLP. With over 15 years of research experience in similarity search, Xiao has published 20+ related papers at top-tier conferences (ICML, SIGMOD, VLDB, WWW, etc.). 

**Haochen Zhang** is currently pursuing his Master's degree at Osaka University. He obtained his Bachelor's degree from Osaka City University in 2023. His research areas of interest encompass data mining, data preprocessing, and NLP. During his internship at NEC, he focused on exploring prompting and fine-tuning LLMs for data preprocessing. He has contributed to the development of Jellyfish -- a leading-edge LLM specifically designed for data preprocessing. 
