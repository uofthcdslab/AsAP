ArAM User Guide
===============

This guide explains the logic behind the **ArAM Framework** and provides a worked example to demonstrate how to articulate assumptions effectively.

The Logic: Premise-Target-Differentiator
----------------------------------------

Assumptions do not exist in a vacuum; they exist as part of an **argument**. To articulate an assumption, we must distinguish between the **Premise** (the assumption itself) and the **Target** (the conclusion or goal it supports).

ArAM introduces a meta-layer called the **Differentiator** to categorize how a premise relates to a target.

The Three Differentiators
~~~~~~~~~~~~~~~~~~~~~~~~~

When analyzing a decision or goal, use these three categories to unearth hidden assumptions:

1.  **Understanding of the Target:** Assumptions about the structural understanding of the concepts (e.g., fairness, safety) that underpin the target.
2.  **Appropriateness of Performed Action:** Assumptions about why the performed action is the "right" choice compared to alternatives (e.g., doing nothing vs. intervening).
3.  **Addressal of the Target:** Assumptions about how the action logically leads to the fulfillment of the target.

**Note on Interconnectedness:**
These categories are not mutually exclusive. A single assumption can cut across all three differentiators—for instance, an assumption about the *Understanding* of a concept often directly informs the *Addressal* of the target. The categories are designed to help you brainstorm and surface premises, not to rigidly box them in.

Worked Example
--------------

**Source:**
Anil, R., Dai, A. M., Firat, O., Johnson, M., Lepikhin, D., Passos, A., ... & Wu, Y. (2023). Palm 2 technical report. *arXiv preprint arXiv:2305.10403*, p.87.

**Context:**
The report provides the following response to a specific question about annotator diversity:

    **Question:** Are there certain annotator perspectives or subgroups whose participation was prioritized? [cite_start]If so, how were these perspectives sought out?
    
    **Response:** No.

**Step 1: Identify the Target**

* **Target:** To perform inclusive hiring of annotators.
* **Is Target Implicit?** No.

**Step 2: Articulate Assumptions using Differentiators**

.. list-table::
   :widths: 25 45 30
   :header-rows: 1

   * - Differentiator
     - Articulation of Assumption (Premise)
     - Analysis
   * - **1. Understanding of the Target**
     - "The default state of the world has equal representation.So there is no need to prioritize any group."
     - The assumer understands "inclusivity" as a baseline state that exists naturally.
   * - **2. Appropriateness of Performed Action**
     - "Of several actions that can be performed, such as leveling up/down representation of a group, doing nothing is the most appropriate action."
     - Justifies inaction as superior to active intervention strategies.
   * - **3. Addressal of the Target**
     - "When no group is explicitly prioritized, hiring is inclusive."
     - Links the action (not prioritizing) to the success of the target.

**Reference:**
Mothilal, R. K., Lalani, F. M., Ahmed, S. I., Guha, S., & Sultana, S. (2025). Talking About the Assumption in the Room. *Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems (CHI '25)*. https://doi.org/10.1145/3706598.3713958
