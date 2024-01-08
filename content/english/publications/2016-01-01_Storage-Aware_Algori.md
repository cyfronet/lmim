---
title: "Storage-Aware Algorithms for Scheduling of Workflow Ensembles in Clouds"
date: "2016-01-01"
authors: ["Piotr Bryk", "Maciej Malawski", "Gideon Juve", "Ewa Deelman"]
publication_types: ["2"]
publication: "Journal of Grid Computing, 142 (2) 359--378. https://doi.org/10.1007/s10723-015-9355-6"
publication_short: "Journal of Grid Computing, 142 (2) 359--378. https://doi.org/10.1007/s10723-015-9355-6"
abstract_short: ""
url_source: "https://doi.org/10.1007/s10723-015-9355-6"
keywords: ["Cloud computing","Cloud storage","Scheduling algorithms","Workflow ensembles"]
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
---
This paper focuses on data-intensive workflows and addresses the problem of scheduling workflow ensembles under cost and deadline constraints in Infrastructure as a Service (IaaS) clouds. Previous research in this area ignores file transfers between workflow tasks, which, as we show, often have a large impact on workflow ensemble execution. In this paper we propose and implement a simulation model for handling file transfers between tasks, featuring the ability to dynamically calculate bandwidth and supporting a configurable number of replicas, thus allowing us to simulate various levels of congestion. The resulting model is capable of representing a wide range of storage systems available on clouds: from in-memory caches (such as memcached), to distributed file systems (such as NFS servers) and cloud storage (such as Amazon S3 or Google Cloud Storage). We observe that file transfers may have a significant impact on ensemble execution; for some applications up to 90 % of the execution time is spent on file transfers. Next, we propose and evaluate a novel scheduling algorithm that minimizes the number of transfers by taking advantage of data caching and file locality. We find that for data-intensive applications it performs better than other scheduling algorithms. Additionally, we modify the original scheduling algorithms to effectively operate in environments where file transfers take non-zero time.
