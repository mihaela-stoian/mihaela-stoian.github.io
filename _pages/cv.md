---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[//]: # (My CV is available [here]&#40;https://github.com/mihaela-stoian/mihaela-stoian.github.io/blob/main/files/cv/MihaelaCatalinaStoian_CV09.pdf&#41;.)
**My CV is available [here](https://mihaela-stoian.github.io/files/cv/CV_Mihaela_Catalina_Stoian.pdf).**

{% include base_path %}

----

Interests
======
Neuro-Symbolic AI • Knowledge-Aided ML • Deep Generative Models • Large Language Models

I build neuro-symbolic AI systems that inject background-knowledge requirements into neural networks during training and guarantee those requirements are satisfied. My focus is making these knowledge-aided frameworks practical for real-world use — synthesising tabular data, autonomous driving, and constraining large language models for theorem proving.

Education
======
* **DPhil in Computer Science**, University of Oxford (2021–2026)
  + Thesis: [Knowledge-Refined Deep Neural Networks for Real-World Applications](https://ora.ox.ac.uk/objects/uuid:c57569ac-c6b7-4188-af61-88a741bf58e6)
  + Supervisor: Prof. Thomas Lukasiewicz
  + Areas: deep learning, generative modelling, autonomous driving, neuro-symbolic AI
* **Master of Informatics with Honours, First Class**, The University of Edinburgh (2014–2019)
  + Supervisor: Prof. Sharon Goldwater
  + Areas: NLP, speech-to-text machine translation, speech processing

Work Experience
======
* **Research Associate** at Imperial College London, UK (2025–present)
  + PI: Dr. Eleonora Giunchiglia
  + Autoformalisation: building methods to constrain language models so they translate informal mathematics into formal statements verifiable by proof assistants such as Lean.
  + Funded by Renaissance Philanthropy.

* **Research Intern — Computer Vision & Autonomous Vehicles** at FiveAI, Oxford, UK (2020–2021)
  + Supervisor: Dr. Tommaso Cavallari
  + 3D symmetry detection: designed a method that estimates planar reflective symmetries on 3D inputs by slicing along the height dimension and feeding slices to a 2D convolutional recurrent regressor, avoiding costly 3D convolutions.
  + [Paper](https://arxiv.org/abs/2106.16129): Recurrently Estimating Reflective Symmetry Planes from Partial Pointclouds (CVPR 2021 Workshop on 3D Vision and Robotics).
  + Patent: 3D Perception, US 20240212189 A1 (Five AI Ltd, 2024; pending).

* **Research Assistant — NLP & Machine Translation** at The University of Edinburgh, UK (2019)
  + Supervisor: Prof. Sharon Goldwater
  + Speech-to-text translation: showed that ASR pretraining with target-language data augmentation improves translation performance, and that pretrained-ASR word error rate directly predicts translation quality.
  + [Paper](https://arxiv.org/abs/1910.10762): Analyzing ASR pretraining for low-resource speech-to-text translation (Proc. of ICASSP 2020).

* **Summer Research Fellow — Network Verification & Program Synthesis** at ETH Zurich, Switzerland (2018)
  + Supervisors: Prof. Martin Vechev, Asst. Prof. Dana Drachsler Cohen
  + Program synthesis for P4: built a Python parser for P4 (Programming Protocol-Independent Packet Processors) and used the Z3 solver to encode and synthesise intended packet-processing behaviour.

Technical Skills
======
* **Languages** — Python (proficient); C++, Java, Bash/Shell (familiar)
* **Deep learning** — PyTorch, PyTorch Lightning, TensorFlow; Hugging Face, verl
* **ML & data** — scikit-learn, NumPy, SciPy, Pandas, Matplotlib, Seaborn; Jupyter
* **Tooling** — Linux/command line, Git, Docker, Slurm, Conda, Weights & Biases, TensorBoard, LaTeX

Software & Patents
======
* **Software:** PiShield — a PyTorch framework for integrating background-knowledge requirements into neural networks [[github.com/mihaela-stoian/PiShield](https://github.com/mihaela-stoian/PiShield)]
* **Patent:** 3D Perception, US 20240212189 A1 (Five AI Ltd, 2024; pending)

Awards
======
* **[Oxford PhD Runner-up Prize](https://www.gresearch.com/news/g-research-2025-phd-prize-winners-university-of-oxford/)** awarded by G-Research (2025)
* **EPSRC Scholarship for Doctoral Studies** awarded by University of Oxford (2021–2025)
* **Women in Quant Finance Grant** awarded by G-Research (2025)
* **IJCAI Grant** awarded by IJCAI-AIJ (2024)
* **Conference Travel Grants** awarded by St Hilda's College, University of Oxford (2023, 2024)
* **Best Paper Award** at the AI4AD Workshop @ IJCAI (2022)

[//]: # (* **Best Student Paper Prize** at IJCLR &#40;2022&#41;)

Selected Talks
======
* **OxBridge Women in CS Conference**, University of Oxford — selected for oral presentation (2026)
* **Civil Service Leadership Group**, Imperial College London — invitation-only (2025)
  + One of only four projects selected; presented to senior UK civil servants, incl. the Head of the Civil Service.
* **Dagstuhl Seminar on Logic and Neural Networks** — invitation-only (2025)
* **IJCAI Doctoral Consortium** (2024)
* **SnT, University of Luxembourg** — invited (2024)
  + Security, Reasoning and Validation reading group.
* **Sony AI** — invited (2024)
  + Barcelona and Tokyo reading groups.

Mentoring
======
* **Tutorial:** Beyond Soft Penalties: Hard Constraints for Neural Networks with Continuous Outputs — UAI 2026 (forthcoming)
  + Co-presented; introduces methods for enforcing hard constraints over continuous neural network outputs.
* **Co-supervision:**
  + A. Godun — MSc, TU Wien (current)
  + S. Lee — MSc, Imperial College London (2025)
  + L. Pejic — BSc, TU Wien (2025)
* **Teaching** — Class Tutor, University of Edinburgh (2017–2019)
  + Discrete Mathematics & Mathematical Reasoning
  + Algorithms, Data Structures & Learning
  + Processing Formal & Natural Languages

Service
======
* **Workshop & challenge organiser**
  + ROAD++: The Third Workshop & Challenge — ECCV 2024
  + ROAD-R: The Road Event Detection with Requirements Challenge — NeurIPS 2023
  + ROAD++: The Second Workshop & Challenge — ICCV 2023
* **Reviewing**
  + Conferences — NeurIPS, ICLR, ICML, IJCAI, NeSy
  + Journal — Machine Learning
  + Workshops — RepL4NLP @ ACL 2022, NeSy-GeMs @ ICLR 2023

Languages
======
English (proficient) • Romanian (native) • German (elementary)

Publications
======
<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>