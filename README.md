# Detecting and Understanding Vulnerabilities in Language Models via Mechanistic Interpretability

This repository contains the data and code used to perform the experiments of the paper: Detecting and Understanding Vulnerabilities in Language Models via Mechanistic Interpretability. It also includes the supplementary materials.

# How to use

First, clone the repository and install the required dependencies:

```
git clone git@github.com:jgcarrasco/detecting-vulnerabilities-mech-interp.git
cd detecting-vulnerabilities-mech-interp
pip install -r requirements.txt
```

Then, follow along the different Jupyter notebooks to follow the case study presented in the paper. There is a separate notebook for each step.

- `0_building_dataset.ipynb`: BUild the synthetic dataset composed by acronyms that will be used for the preceding steps.
- `1_patching.ipynb`: Apply a series of patching experiments to localize the circuit.
- `2_build_acronyms.ipynb`: Build a set of acronyms with Algorithm 1 that will be used to locate vulnerabilities.
- `3_lens.ipynb`: Locate which components of the circuit are vulnerable via logit lens.
- `4_interpret_vulnerabilities.ipynb`: Interpret what is happening on the identified vulnerable components.