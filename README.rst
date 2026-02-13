AsAP: Articulating Assumptions in Machine Learning
==================================================

.. image:: https://zenodo.org/badge/DOI/10.5281/zenodo.18582385.svg
  :target: https://doi.org/10.5281/zenodo.18582385
  :alt: DOI

.. image:: https://img.shields.io/badge/Citation-CHI%2725-blue.svg
  :target: https://doi.org/10.1145/3706598.3713958
  :alt: Citation
  
**AsAP** (**As**\ assumption-**A**\ s-**P**\ remise) is a methodological framework designed to support Machine Learning practitioners and researchers in articulating implicit assumptions in their workflows.

About
-----

**Context:**
In current ML workflows, assumptions are often constructed independently or lurking within technical processes, handled reactively rather than reflectively, and recorded nebulously. This lack of clear conceptualization leads to confusion, where the trajectory of an assumption often begets *more* assumptions and uncertainties. While many toolkits exist, structured approaches to explicitly articulate these assumptions are rare, and the process is often taken for granted.

**Approach:**
AsAP disambiguates assumption inquiry by treating every technical decision as an *argument* composed of two parts: the target and premises. By separating the *Target* from its *Premises*, AsAP helps you clearly identify *why* a decision was made and *how* it was justified.

* *The Target:* The goal or conclusion you are trying to achieve (e.g., *"We will use Dataset X"*).
* *The Premises (Assumptions):* The reasons that support that goal (e.g., *"Dataset X is representative"*).

**Outcome:**
To operationalize this, the framework introduces a meta-layer called the *differentiator*. The differentiator distinguishes three broad categories in which the premises (assumptions) can be related to the target:

1.  Understanding of the Target
2.  Appropriateness of Performed Action
3.  Addressal of the Target

How to Use
----------

This repository contains two key documents to help you apply AsAP:

1.  **guide.rst**: A detailed explanation of the framework with a real-world example from the PaLM 2 technical report.
2.  **worksheet.rst**: A blank template you can copy to articulate assumptions for your own ML projects.

**Quick Start:**

1.  Open **worksheet.rst**.
2.  Follow the steps to identify your **Target** and use the **Differentiators** to surface your underlying premises/assumptions.

Citation
--------

If you use this framework in your research or documentation, please cite the following paper:

**BibTeX:**

.. code-block:: bibtex

   @inproceedings{mothilal2025assumptions,
     author = {Mothilal, Ramaravind Kommiya and Lalani, Faisal M. and Ahmed, Syed Ishtiaque and Guha, Shion and Sultana, Sharifa},
     title = {Talking About the Assumption in the Room},
     booktitle = {Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems},
     series = {CHI '25},
     year = {2025},
     location = {Yokohama, Japan},
     publisher = {ACM},
     doi = {10.1145/3706598.3713958}
   }

**Text:**
Mothilal, R. K., Lalani, F. M., Ahmed, S. I., Guha, S., & Sultana, S. (2025). Talking About the Assumption in the Room. *Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems (CHI '25)*. https://doi.org/10.1145/3706598.3713958
