# Automated-Interface-Restructuring-for-Mobile-Usability-Improvement
The project proposes an automated framework for generating interface restructuring recommendations to improve the usability of Mobile User Interfaces (MUIs) during early stages of development.

Overview

Usability issues in mobile applications are often identified late in the development lifecycle, where corrective actions become costly and difficult to apply.
This work addresses this challenge by:

detecting usability smells in mobile interfaces,

combining them with quantitative usability metrics, and

generating actionable interface restructuring recommendations using multi-objective evolutionary optimization.

The framework explicitly balances usability improvement with solution simplicity, interpretability, and reliability.


 Key Contributions

Automated detection of usability smells in Mobile User Interfaces

Rule-based modeling of interface restructuring actions

Multi-objective formulation of the restructuring recommendation problem

Adaptation of the Indicator-Based Evolutionary Algorithm (IBEA)

Empirical evaluation on real-world open-source Android applications


 Requirements

Java / Python (depending on implementation)

Evolutionary computation libraries

Statistical analysis tools (e.g., R or Python SciPy)

Android UI layout data (XML)

Detailed dependencies are listed in the project configuration files.

 Reproducibility

To ensure reproducibility:

All experiments are executed over 100 independent runs

Random seeds are controlled and reported

Non-parametric statistical tests (Wilcoxon rank-sum) are used

Parameter configurations are explicitly documented


Acknowledgments

This work builds on prior research in usability engineering, search-based software engineering, and evolutionary optimization. We thank the open-source community for providing the mobile applications used in the empirical evaluation.




