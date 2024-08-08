Overview
==========
This site contains the course materials for  the [**ESSLLI 2024**](https://2024.esslli.eu/placeholder-programme/course-overview.html) course of **Language Model Programming**. 

**overview** When developing complex AI systems, which nowadays couple many individual components and tools (e.g., code interpreters, search technology) with **large language models** (LLMs), a natural question arises: *how can users and developers of these systems compose model components into a coherent system to best achieve their goals?* Such is the problem of **language model programming**, which concerns how the underlying components of AI systems are assembled, the nature of the interaction between components, and, importantly, the *language that users use to specify the design and implementation of these systems*. In this course, we explore this emerging literature on model language programming, looking at the fundamentals of how to build high-level modeling languages for LLMs, the different *paradigms* of model programming that exist (e.g., [functional](https://arxiv.org/pdf/2106.06981) vs  [imperative](https://arxiv.org/abs/2212.06094) vs. [declarative](https://dl.acm.org/doi/abs/10.1145/3591280) vs. [probabilistic](https://arxiv.org/pdf/2207.10342)) and the problems in NLP that they address and aim to solve (e.g., theoretical understanding of transformers, model fine-tuning, modular prompting, self-consistency, constrained decoding). 

Lecturers 
==========

[**Kyle Richardson**](https://www.krichardson.me/) (Allen Institute for AI) 
[**Gijs Wijnholds**](https://gijswijnholds.github.io/) (Leiden Institute of Advanced Computer Science)

Slides 
==========

[**lecture 1**](https://github.com/yakazimir/esslli_2024_llm_programming/blob/main/slides/lecture1.pdf): course overview, **language modeling basics**, [**RASP**](https://arxiv.org/pdf/2106.06981). [**extended notes on transformers**](https://www.krichardson.me/files/lms.pdf)

[**lecture 2**](https://github.com/yakazimir/esslli_2024_llm_programming/blob/main/slides/lecture2.pdf): declarative approaches to **model training and fine-tuning**, the [**semantic loss**](https://arxiv.org/pdf/1711.11157) and [**weighted model counting**](https://www.sciencedirect.com/science/article/pii/S0004370207001889),  [**other**](https://arxiv.org/abs/1909.00126) approaches. [**background logic notes**](https://github.com/yakazimir/esslli_2024_llm_programming/blob/main/slides/logic_background.pdf)

[**lecture 3**](https://github.com/yakazimir/esslli_2024_llm_programming/blob/main/slides/lecture3.pdf): declarative and [**probabilistic**](https://www.khoury.northeastern.edu/home/lieber/courses/csg260/f06/materials/papers/bayes/AAAI02-102.pdf) approaches to **structured inference**, [**LLM self-correction**](https://arxiv.org/abs/2211.11875). 

[**lecture 4**](https://github.com/yakazimir/esslli_2024_llm_programming/blob/main/slides/lecture4.pdf) LLM decoding, promting, [**prompting is programming and LMQL**](https://arxiv.org/pdf/2212.06094).

Helpful Resources 
==========

Below are some pointers to code resources:
- **solvers** [[Z3 solver]](https://github.com/Z3Prover/z3), [[python-sat]](https://pysathq.github.io/), [[problog]](https://github.com/ML-KULeuven/problog), [[pyDatalog]](https://github.com/pcarbonn/pyDatalog)

- **NLP and general ML** [[transformers]](https://github.com/huggingface/transformers), [[PyTorch]](https://pytorch.org/), [[pylon-lib]](https://github.com/pylon-lib/pylon), [[hf datasets]](https://huggingface.co/docs/datasets/index)

- **knowledge compilation** [[pysdd]](https://github.com/wannesm/PySDD) 

- **other useful utilities** [[sympy]](https://www.sympy.org/en/index.html), [[lmql]](https://github.com/eth-sri/lmql)
