---
title: "Cost Optimization of Execution of Multi-Level Deadline-Constrained Scientific Workflows on Clouds"
date: "2014-01-01"
authors: ["Maciej Malawski", "Kamil Figiela", "Marian Bubak", "Ewa Deelman", "Jarek Nabrzyski"]
publication_types: ["1"]
publication: " In Roman Wyrzykowski, Jack Dongarra, Konrad Karczewski & Jerzy Waśniewski: Parallel Processing and Applied Mathematics. 1  251--260. Berlin, Heidelberg: Springer https://doi.org/10.1007/978-3-642-55224-3_24. ISBN: 978-3-642-55224-3"
publication_short: " In Roman Wyrzykowski, Jack Dongarra, Konrad Karczewski & Jerzy Waśniewski: Parallel Processing and Applied Mathematics. 1  251--260. Berlin, Heidelberg: Springer https://doi.org/10.1007/978-3-642-55224-3_24. ISBN: 978-3-642-55224-3"
abstract_short: ""
keywords: ["AMPL optimization","Cloud computing","Scientific workflows"]
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
types: ["Conference/workshop paper"]
---
This paper introduces a cost optimization model for scientific workflows on IaaS clouds such as Amazon EC2 or RackSpace. We assume multiple IaaS clouds with heterogeneous VM instances, with limited number of instances per cloud and hourly billing. Input and output data are stored on a Cloud Object Store such as Amazon S3. Applications are scientific workflows modeled as DAGs as in the Pegasus Workflow Management System. We assume that tasks in the workflows are grouped into levels of identical tasks. Our model is specified in AMPL modeling language and allows us to minimize the cost of workflow execution under deadline constraints. We present results obtained using our model and the benchmark workflows representing real scientific applications such as Montage, Epigenomics, LIGO. We indicate how this model can be used for scenarios that require resource planning for scientific workflows and their ensembles.
