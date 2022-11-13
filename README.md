## Purpose of this analysis

This repository contains code for the development of a simplified scoring system designed to assess eligibility to antiviral treatment for sub-Saharan African patients chronically infected with HEpatitis B virus (HBV) in low-resource contexts, without the need for either liver biopsy, transient elastography, or PCR.

To do so, we performed a meta-analysis based on individual patient data (IPD), with the goal to identify relevant and easily accessible predictors of treatment eligibility. We then sought to produce a simplified scoring system taking such predictors into account to reliably predict eligibility to treatment without the need of liver biopsy, transient elastography, or PCR. To do so, we relied on the HEPatitis B in sub-Saharan Africa NETwork (HEPSANET, see below), which assembled a 4000 participants large cohort of patients chronically infected by HBV coming from 13 cohorts representing 8 sub-Saharan African countries, and considered EASL 2017 guidelines as clinical reference standard.

The simplified scoring system developed here is largely based on the methodology described by [Sullivan and colleagues in 2004](https://doi.org/10.1002/sim.1742), and is similar in concept to that developed by [Shimakawa and colleagues in 2018](https://doi.org/10.1016/j.jhep.2018.05.024) which shared the same goal.

Data analysis was performed on [STATA 17](https://www.stata.com/), and organized in 3 main files:

* Data management, which loads the HEPSANET database and produces a clean dataset and considers exclusion criteria specific to this analysis.
* Reference scoring, which loads the clean dataset and scores each participant according to clinical reference standard (EASL 2017) and comparative criteria (WHO 2015, and TREAT-B)
* Data analysis, which produces the simplified scoring system and performs statistical analysis (performance, agreement, comparison, subgroup analysis, ...)

<b>NB: Code will be made available upon publication of the work in a peer-reviewed scientific journal.</b>

## HEPSANET consortium
The HEPatitis B in sub-Saharan Africa NETwork (HEPSANET) is a consortium of hospitals and research centers across 8 sub-Saharan African countries, in collaboration with several European research institutes.
