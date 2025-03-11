[![Build Status](https://github.com/IBM/LNN/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/IBM/LNN/actions/workflows/build.yml?query=branch%3Amaster)
[![PRs Welcome](https://img.shields.io/static/v1?label=PRs&message=welcome&color=green&logo=git&logoColor=white)](https://makeapullrequest.com)
[![License](https://img.shields.io/static/v1?label=License&message=Apache%202.0&color=blueviolet&logo=linux&logoColor=white)](https://github.com/IBM/LNN/blob/master/LICENSE)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/5926/badge)](https://bestpractices.coreinfrastructure.org/projects/5926)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

# Logical Neural Networks
LNNs are a novel `Neuro = Symbolic` framework designed to seamlessly provide key
properties of both neural nets (learning) and symbolic logic (knowledge and reasoning).

- Every neuron has a meaning as a component of a formula in a weighted
  real-valued logic, yielding a highly interpretable disentangled representation.
- Inference is omnidirectional rather than focused on predefined target
  variables, and corresponds to logical reasoning, including classical
  first-order logic theorem proving as a special case.
- The model is end-to-end differentiable, and learning minimizes a novel loss
  function capturing logical contradiction, yielding resilience to inconsistent
  knowledge.
- It also enables the open-world assumption by maintaining bounds on truth values
  which can have probabilistic semantics, yielding resilience to incomplete
  knowledge.

## Quickstart
To install the LNN:

1. Make sure that the python version you use in line with our [setup](https://github.com/IBM/LNN/blob/master/setup.py) file, using a fresh environment is always a good idea:
    ```commandline
    conda create -n lnn python=3.9 -y
    conda activate lnn
    ```
2. Install the `master` branch to keep up to date with the latest supported features:
    ```commandline
    pip install git+https://github.com/IBM/LNN
    ```

# Akila Sampath - Certifications & Badges

#### 🎖 Certifications & Badges

### **Neuro-Symbolic AI Reasoning Badge**

As part of coursework on Neuro-symbolic AI, I earned this badge for demonstrating foundational knowledge and the ability to formulate AI reasoning problems within a **neuro-symbolic framework**. The badge holder has the ability to:

* Create a **Logical Neural Network (LNN)** model from logical formulas.
* Perform **inference using LNNs**.
* Explain the **logical interpretation of LNN models**.

🔗 **https://www.credly.com/badges/d2a9e4b2-b718-4267-9c05-6ae8e3c9b935**  
[View Certificate]([[./Neuro-Symbolic_AI_Reasoning_Badge.pdf](https://github.com/akilasampath5/LNN/blob/AkilaSampath-Badge/Neuro_Symbolic_AI_Essentials_Badge20231210-29-62js8v.pdf)](https://github.com/akilasampath5/LNN/blob/AkilaSampath-Badge/Neuro_Symbolic_AI_Essentials_Badge20231210-29-62js8v.pdf))

