+++
title = "Logit Pairing Methods Can Fool Gradient-Based Attacks"
date = 2018-01-01
authors = ["Marius Mosbach", "Maksym Andriushchenko", "Thomas Trost", "Matthias Hein", "Dietrich Klakow"]
publication_types = ["2"]
abstract = ""
selected = "false"
publication = "*arXiv preprint arXiv:1810.12042*"
+++

Recently, several logit regularization methods have been proposed in [Kannan et al., 2018] to improve the adversarial robustness of classifiers. We show that the proposed computationally fast methods - Clean Logit Pairing (CLP) and Logit Squeezing (LSQ) - just make the gradient-based optimization problem of crafting adversarial examples harder, without providing actual robustness. For Adversarial Logit Pairing (ALP) we find that it can give indeed robustness against adversarial examples and we study it in different settings. Especially, we show that ALP may provide additional robustness when combined with adversarial training. However, the increase is much smaller than claimed by [Kannan et al., 2018]. Finally, our results suggest that evaluation against an iterative PGD attack relies heavily on the parameters used and may result in false conclusions regarding the robustness. 