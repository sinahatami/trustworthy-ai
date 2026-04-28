<div align="center">
  
  # 🛡️ Trustworthy AI

  **Lab Sessions & Projects for the Trustworthy AI Course**<br>
  *University of Genoa (UniGe)*

  <p>
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
    <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white">
    <img alt="SecML" src="https://img.shields.io/badge/SecML-Security_Evaluation-blueviolet?style=for-the-badge">
  </p>
</div>

---

## 📖 About The Course

This repository contains the laboratory exercises, notebooks, and projects completed for the **Trustworthy AI** course at the **University of Genoa**. 

The course focuses on the vulnerabilities of machine learning algorithms and the techniques used to evaluate, defend, and explain AI models. We explore various adversarial attacks (like Evasion and Poisoning) and countermeasures (like Adversarial Training) primarily using the [SecML](https://secml.gitlab.io/) library.

---

## 🧪 Labs Overview

Here is a breakdown of the interactive Jupyter notebooks included in this repository:

| Notebook | Description | Concepts Covered |
| :--- | :--- | :--- |
| `00-SecML` | **Introduction to SecML** | Basic operations with `CArray`, data loading, model training, and performance evaluation. |
| `01-Evasion_complete` | **Adversarial Evasion Attacks** | Implementing PGD (Projected Gradient Descent) attacks, generating adversarial examples to fool classifiers. |
| `02-AdversarialEXEmples` | **Malware Evasion (Adversarial EXEmples)** | Crafting adversarial Windows PE malware files to bypass machine learning-based malware detectors. |
| `03-AdversarialTraining` | **Adversarial Training & Defenses** | Hardening machine learning models against adversarial attacks by incorporating adversarial examples into the training phase. |
| `05-Poisoning_complete` | **Data Poisoning Attacks** | Corrupting the training dataset to compromise the learning process and degrade model performance. |
| `06-Explainability` | **Explainable AI (XAI)** | Interpreting model decisions, understanding feature importance, and visualising how models make predictions. |
| `FINAL-PART2` | **Final Project** | Comprehensive application of the concepts learned throughout the course. |

---

## 🚀 Getting Started

To run these notebooks locally, you will need a Python environment with the required dependencies installed.

### Prerequisites

We recommend using `venv` or `conda` to manage your environment. The primary library used across these labs is **SecML**.

```bash
# Clone the repository
git clone https://github.com/yourusername/trustworthy-ai.git
cd trustworthy-ai

# Create a virtual environment
python3 -m venv .venv
source .venv/bin/activate

# Install Jupyter and SecML
pip install jupyterlab secml secml-malware lief
```

### Running the Labs

Once the environment is set up, you can start Jupyter Lab to explore the notebooks:

```bash
jupyter lab
```

---

## 📚 Acknowledgments

* Course Instructors and TAs from the University of Genoa.
* The [SecML project](https://secml.gitlab.io/) developers for providing an excellent framework for secure and trustworthy machine learning.

<br>
<div align="center">
  <sub>Built with 💙 for the Trustworthy AI course.</sub>
</div>
