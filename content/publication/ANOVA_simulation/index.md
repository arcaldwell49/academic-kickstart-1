+++
#abstract = ""
abstract = "Researchers often rely on analysis of variance (ANOVA) when they report results of experiments. To ensure a study is adequately powered to yield informative results when performing an ANOVA, researchers can perform an a-priori power analysis. However, power analysis for factorial ANOVA designs is often a challenge. Current software solutions do not allow power analyses for complex designs with several within-subject factors. Moreover, power analyses often need partial eta-squared or Cohen's *f* as input, but these effect sizes are not intuitive and do not generalize to different experimental designs. We have created the R package Superpower and online Shiny apps to enable researchers without extensive programming experience to perform simulation-based power analysis for ANOVA designs of up to three within- or between-subject factors. Predicted effects are entered by specifying means, standard deviations, and for within-subject factors the correlations. The simulation provides the statistical power for all ANOVA main effects, interactions, and individual comparisons, and allows researchers to correct for multiple comparisons. The software can plot power across a range of sample sizes, can control error rates for multiple comparisons, and can compute power when the homogeneity or sphericity assumptions are violated. This tutorial will demonstrate how to perform a-priori power analysis to design informative studies for main effects, interactions, and individual comparisons, and highlights important factors that determine the statistical power for factorial ANOVA designs."
authors = ["Daniel Lakens", "Aaron R. Caldwell"]
date = "2019-05-21"
#image_preview = "headers/es-plot.png"
math = false
publication_types = ["1"]
publication = "Advances in Methods and Practices in Psychological Science"
publication_short = "ANOVA Simulations"
selected = true
featured = false
title = "Simulation-Based Power-Analysis for Factorial ANOVA Designs"
# url_code = ""
# url_dataset = ""
url_pdf = "pdf/ANOVA_sim.pdf"
url_project = "https://aaroncaldwell.us/Superpower"
# url_slides = ""
# url_video = ""



# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/es-plot.png"
#caption = ""

+++

A tutorial article on using the Superpower R package.

**Citeable as**:

Lakens, D., & Caldwell, A. R. (2019). Simulation-Based Power-Analysis for Factorial ANOVA Designs. *PsyArXiv* https://doi.org/10.31234/osf.io/baxsf
