## Predictive Modeling of Health Disparities Among Hispanics Using Hepatitis C Virus Data

### Project Overview

This project applies supervised machine learning techniques to investigate health disparities among Hispanic populations in the United States using **Hepatitis C Virus (HCV)** clinical data obtained from the **University of Puerto Rico Medical Center**, in collaboration with the **Center for Collaborative Research**. The objective was to evaluate and compare the predictive performance of multiple classifiers in modeling HCV-related outcomes within this population.

### Data Source

*   **Institution:** University of Puerto Rico Medical Center
*   **Collaboration:** Center for Collaborative Research
*   **Population of Interest:** Hispanic individuals within the U.S.
*   **Domain:** Hepatitis C Virus (HCV) clinical and demographic data

### Methodology

Six widely used machine learning classifiers were trained and evaluated on the dataset. Model performance was assessed using **predictive accuracy** and **mean squared error (MSE)** to balance classification effectiveness and prediction stability.

The classifiers implemented were:

*   Logistic Regression (LR)
*   Linear Discriminant Analysis (LDA)
*   k-Nearest Neighbors (KNN)
*   Classification and Regression Tree (CART)
*   Naïve Bayes (NB)
*   Support Vector Machine (SVM)

### Model Performance

The final predictive results for each classifier are summarized below. Values in parentheses correspond to **MSE**.

*   **Logistic Regression (LR):**  
    Accuracy = **0.822348**, MSE = **0.017031**

*   **Linear Discriminant Analysis (LDA):**  
    Accuracy = **0.825645**, MSE = **0.013550**

*   **k-Nearest Neighbors (KNN):**  
    Accuracy = **0.836550**, MSE = **0.028316**

*   **Classification and Regression Tree (CART):**  
    Accuracy = **0.824546**, MSE = **0.029151**

*   **Naïve Bayes (NB):**  
    Accuracy = **0.699689**, MSE = **0.073585**

*   **Support Vector Machine (SVM):**  
    Accuracy = **0.864035**, MSE = **0.026069**

### Key Findings

*   The **Support Vector Machine (SVM)** achieved the highest predictive accuracy, indicating strong performance in handling complex decision boundaries within the HCV dataset.
*   **Naïve Bayes** showed comparatively lower accuracy and higher error, suggesting weaker assumptions of feature independence for this clinical context.
*   Overall, the results highlight meaningful variability in classifier effectiveness when modeling health outcomes for Hispanic populations, underscoring the importance of model selection in health disparity research.

### Significance

This study demonstrates the applicability of machine learning methods in analyzing HCV-related health disparities and provides a comparative framework for predictive modeling in epidemiological and public health research involving underrepresented populations.

Below is a **scholarly, proposal‑ready explanation** that clearly articulates **how AI and ML were central to your analysis** and **how this work logically feeds into your proposed endeavor** (e.g., dissertation, grant, or expanded research agenda). I’ve framed it at a level suitable for academic review panels, interdisciplinary collaborators, and funding agencies.

***

## Role of Artificial Intelligence and Machine Learning in the Analysis

Artificial intelligence (AI) and machine learning (ML) were instrumental in enabling a rigorous, scalable, and data-driven investigation of health disparities among Hispanic populations using Hepatitis C Virus (HCV) data. Traditional statistical approaches often rely on strong parametric assumptions and linear relationships, which can be limiting when analyzing complex clinical and sociodemographic data. In contrast, ML methods allowed the analysis to capture **nonlinear patterns, interactions among variables, and latent structures** that are characteristic of real-world health data.

In this study, supervised machine learning algorithms were used to **learn predictive relationships directly from patient-level data**, rather than imposing predefined functional forms. By training six distinct classifiers—Logistic Regression, Linear Discriminant Analysis, K-Nearest Neighbors, CART, Naïve Bayes, and Support Vector Machines—the analysis systematically compared differing learning paradigms, including probabilistic, distance-based, tree-based, and margin-based methods. This comparative framework is a hallmark strength of applied AI, as it enables empirical evaluation of model suitability for a given health context.

Beyond prediction, AI methods contributed to **model robustness and validation**. Performance metrics such as predictive accuracy and mean squared error (MSE) provided complementary perspectives on classification effectiveness and error stability. This dual evaluation ensured that model success was not solely driven by accuracy but also by consistent generalization performance—an essential consideration for translational health research.

## Advancing Health Disparities Research Through ML

AI and ML were especially valuable in addressing health disparities because they facilitate **population-specific modeling**. Hispanic populations are often underrepresented or aggregated in national health datasets, which can obscure clinically relevant heterogeneity. Machine learning techniques enabled the isolation and analysis of patterns within this specific demographic group using institutional clinical data from the University of Puerto Rico Medical Center.

The superior performance of more flexible models, particularly the Support Vector Machine, underscores the importance of AI-driven approaches when dealing with **complex, multidimensional health determinants**. These models demonstrated enhanced capacity to discriminate outcomes in the presence of varying clinical profiles, thus providing a more nuanced understanding of disease burden within the population studied.

## How This Work Feeds Into the Proposed Endeavor

This analysis serves as a **foundational proof of concept** by demonstrating that AI-driven predictive modeling can meaningfully enhance the study of health inequities in Hispanic populations. The results establish both methodological feasibility and empirical justification for expanding the scope of AI applications in this domain.

Specifically, this work feeds into the proposed endeavor in several key ways:

1.  **Methodological Framework**  
    The multi-model ML pipeline developed here provides a reusable and extendable framework for future studies. It can be scaled to incorporate additional data sources (e.g., longitudinal records, social determinants of health, or multi-site datasets), enabling more comprehensive modeling of disparities.

2.  **Decision-Support Potential**  
    The predictive insights generated through AI models lay the groundwork for developing **clinical decision-support tools** or population-risk stratification systems. These tools can assist clinicians and public health stakeholders in identifying high-risk subgroups and tailoring interventions more effectively.

3.  **Precision and Equity-Oriented Research**  
    By leveraging machine learning to move beyond one-size-fits-all assumptions, my work aligns with precision medicine and **equitable AI** objectives. The proposed endeavor can build on this foundation to explore fairness-aware modeling, bias mitigation, and interpretability in health AI applications.

4.  **Interdisciplinary and Translational Impact**  
    The integration of AI techniques with clinical and epidemiological expertise positions your research at the intersection of data science, public health, and health equity. This strengthens the translational potential of your proposed endeavor, making it relevant for academic, clinical, and policy-oriented audiences.

## Significance Moving Forward

In summary, AI and ML were not merely analytical tools but **central enablers of innovation** in this study. They allowed for deeper insight into HCV-related health disparities among Hispanics, supported rigorous model comparison, and produced actionable predictive knowledge. This work directly informs your proposed endeavor by providing a validated analytical foundation upon which more advanced, interpretable, and equity-centered AI systems can be developed.

