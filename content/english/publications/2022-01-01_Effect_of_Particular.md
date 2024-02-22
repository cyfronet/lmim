---
title: "Effect of Particularisation Size on the Accuracy and Efficiency of a Multiscale Tumours' Growth Model"
date: "2022-01-01"
authors: ["Vinicius Varella", "Barbara de M. Quintela", "Marek Kasztelnik", "Marco Viceconti"]
publication_types: ["2"]
publication: "International Journal for Numerical Methods in Biomedical Engineering, 382 (12) e3657. https://doi.org/10.1002/cnm.3657"
publication_short: "International Journal for Numerical Methods in Biomedical Engineering, 382 (12) e3657. https://doi.org/10.1002/cnm.3657"
abstract_short: ""
url_source: "https://onlinelibrary.wiley.com/doi/abs/10.1002/cnm.3657"
keywords: ["homogenisation","in-silico","modelling","multiscale","oncology","particularisation"]
url_code: ""
image_preview: ""
selected: false
projects: []
url_pdf: ""
url_preprint: ""
url_dataset: ""
url_project: ""
url_slides: ""
url_video: ""
url_poster: ""
math: true
highlight: true
image: ""
caption: ""
types: ["Journal Article"]
---
In silico, medicine models are frequently used to represent a phenomenon across multiples space–time scales. Most of these multiscale models require impracticable execution times to be solved, even using high performance computing systems, because typically each representative volume element in the upper scale model is coupled to an instance of the lower scale model; this causes a combinatory explosion of the computational cost, which increases exponentially as the number of scales to be modelled increases. To attenuate this problem, it is a common practice to interpose between the two models a particularisation operator, which maps the upper-scale model results into a smaller number of lower-scale models, and an operator, which maps the fewer results of the lower-scale models on the whole space–time homogenisation domain of upper-scale model. The aim of this study is to explore what is the simplest particularisation / homogenisation scheme that can couple a model aimed to predict the growth of a whole solid tumour (neuroblastoma) to a tissue-scale model of the cell-tissue biology with an acceptable approximation error and a viable computational cost. Using an idealised initial dataset with spatial gradients representative of those of real neuroblastomas, but small enough to be solved without any particularisation, we determined the approximation error and the computational cost of a very simple particularisation strategy based on binning. We found that even such simple algorithm can significantly reduce the computational cost with negligible approximation errors.
