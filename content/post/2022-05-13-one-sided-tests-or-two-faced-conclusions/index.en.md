---
title: One sided tests or two faced conclusions?
author: Aaron R. Caldwell
date: '2022-05-13'
slug: []
categories: []
tags:
  - statistics
  - hypothesis testing
subtitle: ''
summary: 'A quick set of thoughts on a current controversy'
authors: []
lastmod: '2022-05-13T17:05:26-04:00'
featured: no
bibliograpy: ref.bib
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---

Over the past few days there has been a controversy stirring about on Twitter regarding a psychedelic drug and claims regarding their efficacy in psychotherapy. I have no interest in the debate on the efficacy, but it did bring an interesting debate on directional hypotheses and the use of one- and two-sided statistical tests. In particular, the irascible James Heathers [brought attention](https://twitter.com/jamesheathers/status/1524717369439965187?s=20&t=Fm4K3gQi9oKgGfv1fhhtMA) to the fact that the authors used one-sided tests in a suspicious manner.

# Abusing statistical tests

-   JAPPL article

# The right test for the hypothesis

## Examples of non-directional hypotheses

## Examples of directional hypotheses

# "Thus Saith the P-value"

Some of the thoughts spreading around Twitter on one-sided tests show a rigid thought process when it comes to interpreting data from an experiment. In my conversation with [Hannibal], she seemed to indicate that one could only report and indication of an effect in the opposite direction of the hypothesis if there was a statistical test that indicated such. 

From a hypothesis testing perspective, I find this very silly. If the hypothesis test does not reject the null (frequentist/NHST) or does not find relative evidence in favor alternative hypothesis (Bayesian), then we accept the null hypothesis. In my opinion, that's it for hypothesis tests and the statistical tools used to generate such tests. If the null hypothesis is accepted (e.g., one-sided t-test with a p-value greater than the alpha-level), the the job of the researcher is to investigate the data further and provide a reasonable set of explanations as to why their hypothesis could have been wrong *and* the limitations of the study that may have led to the failure to reject the null hypothesis. Moreover, hypothesis tests are not needed at this point because *no hypothesis is being tested*. The job at this point isn't to come to any certainty regarding the phenomena being studied, but to explore other possibilities and advise others in the scientific community where to investigate next.

A major point of contention seems to be if the directional hypothesis is so wrong that estimated effect is in the opposite direction. From my point of view, there is no problem for a researcher to bring up to the fact that the sign of the effect is in the opposite direction. That is what the data indicates whether people like it or not. If the point estimate is the opposite direction then the effect is *more likely* to be negative than positive. I'd say a researcher would be derelict in their reporting duties if they do not bring up this up in their discussion of the results. In these cases, not only was the researcher's hypothesis wrong it was so wrong as to indicate the opposite *could* be true.


It is rather lazy to simply make decisions on what or what not to report based on a single statistical tests.
If science could be boiled down to a few statistical tests that decide what and how to interpret a study then we might as well create bots to write our manuscript for us.

# Conclusion

To be honest, I am a little disturbed by the conversation surrounding one-sided tests because it feels like skepticism of other scientists' work curdling into cynicism. I have in the past advocated for greater statistical scrutiny of scientific publications, but I believe criticisms like "one-sided tests are suspicious" are rather short sighted. Certainly, as I have detailed above, there are cases where one-sided tests are utilized for nefarious purposes, but that is dependent upon the context within which they are utilized. Creating an environment where one sided tests are immediately treated with suspicion is *not* ideal. In fact, I tend to agree with my friend Daniel Lakens, if the hypothesis has a specific direction that involves a "Go-No Go" decision then the one-sided test or directional test should be the default.

# Unanswered questions

1.  I am still not sure why the FDA requires an alpha 0.025 for one-tailed tests. If anyone has any manuscripts or regulatory doucments outlining this reasoning in detail I would greatly appreciate it.
