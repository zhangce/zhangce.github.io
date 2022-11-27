---
title: Research
layout: home
has_children: false
has_toc: false
nav_order: 2
---

## Research

_Today’s machine learning and artificial intelligence are limited by their costs_ --- Training a model can easily take million of dollars, while acquiring, cleaning, and improving the underlying datasets to enforce model quality, fairness, and robustness is no cheaper. These costs come from different, closely-coupled sources: (1) the staggering amount computation, storage and communication that these models need, (2) the cost of infrastructure ownership in today’s centralized cloud, (3) the cost of data acquisition, cleaning, and debugging and associated human costs, (4) the cost of regulation compliance, and (5) the cost of operational deployment such as monitoring, continuous testing, and continuous adaptation.

The key belief behind my research is that _we need to bring the costs down, by orders of magnitude, in all these fronts to bring ML/AI into a trustworthy and democratized future_. In order to achieve this goal, our research focuses on building machine learning systems, enabled by novel algorithms, theory, and system optimizations and abstractions. Our research falls into two directions.

## Project Zip.ML: Distributed and Decentralized Learning at Scale

<img align="right" src="https://github.com/zhangce/zhangce.github.io/blob/4f195a8bdffbafbed1e410fd13636c01b42efd67/images/BaguaLogo.png?raw=true" width="55px"/> [**Bagua**](https://github.com/BaguaSys/bagua) <img width="50px" src="https://img.shields.io/github/stars/BaguaSys/bagua.svg"> <ins>_Distributed learning with system relaxations: Decentralization, Asynchronization, Compression_</ins> 
  - Also available in [Pytorch Lightening  (`BaguaStrategy`)](https://pytorch-lightning.readthedocs.io/en/latest/api/pytorch_lightning.strategies.BaguaStrategy.html)!
  - Main System Reference:  [_BAGUA: Scaling up Distributed Learning with System Relaxations_](https://arxiv.org/abs/2107.01499), **VLDB'22**.
<img align="right" src="https://assets.thalia.media/img/artikel/9071fc0b91de81745798522e154c648539b5f35f-00-00.jpeg" width="50px"/>
  - Main Theory Reference: [_Distributed Learning Systems with First-order Methods_](https://arxiv.org/abs/2104.05245), 2021. --- A summary of our explorations on the theory side over the years at **NeurIPS** [['17a](https://arxiv.org/abs/1705.09056), ['18](https://arxiv.org/abs/1803.06443), ['22a](https://arxiv.org/abs/2206.01288), ['22b](https://arxiv.org/abs/2206.01299)] and **ICML** [['18a](https://arxiv.org/abs/1710.06952), ['18b](https://arxiv.org/abs/1803.07068), ['19](https://arxiv.org/abs/1810.07766), ['20](https://proceedings.mlr.press/v119/fu20c.html), ['21](https://arxiv.org/abs/2102.02888)] .
  
<img align="right" src="https://avatars.githubusercontent.com/u/86388477?s=200&v=4" width="55px"/> [**Persia**](https://github.com/PersiaML/PERSIA) <img width="50px" src="https://img.shields.io/github/stars/PersiaML/PERSIA.svg"> <ins>_Deep Recommendation Models at 100 Trillion Parameter Scale_</ins>
  - Main Reference: [_Persia: An Open, Hybrid System Scaling Deep Learning-based Recommenders up to 100 Trillion Parameters_](https://arxiv.org/abs/2111.05897), **SIGKDD'22**.
  - Blog from Google Cloud: [_Training Deep Learning-based recommender models of 100 trillion parameters over Google Cloud_](https://cloud.google.com/blog/products/ai-machine-learning/training-a-recommender-model-of-100-trillions-parameters-on-google-cloud)

<img align="right" src="https://github.com/zhangce/zhangce.github.io/blob/master/images/Gauss.png?raw=true" width="55px"/> [**OpenGauss DB4AI**](https://opengauss.org/en/) <img width="50px" src="https://img.shields.io/github/stars/opengauss-mirror/openGauss-server.svg"> <ins>_In-Database Machine Learning with deep physical integration_</ins>
  - Main Reference: [_In-Database Machine Learning with CorgiPile: Stochastic Gradient Descent without Full Data Shuffle_](https://arxiv.org/abs/2206.05830), **SIGMOD'22**.

<img align="right" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Greek_lc_lamda.svg/1200px-Greek_lc_lamda.svg.png" width="55px"/> [**LambdaML**](https://github.com/DS3Lab/LambdaML) <img width="50px" src="https://img.shields.io/github/stars/DS3Lab/LambdaML.svg"> <ins>_Distributed machine learning over serverless infrastructure_</ins>
  - Main Reference: [_Towards Demystifying Serverless Machine Learning Training_](https://arxiv.org/abs/2105.07806), **SIGMOD'21**.

## Project Ease.ML: Data-centric ML DevOps

<img align="right" src="https://ds3lab.inf.ethz.ch/easeml/_jcr_content/par/fullwidthimage/image.imageformat.fullwidth.58888527.png" width="250px"/> [**Ease.ML Family**](https://ds3lab.inf.ethz.ch/easeml.html) <ins>_End-to-end Lifecycle management for ML DevOps: Rethinking Data Quality for Machine Learning_</ins>
- System Overview: [_Ease.ML: A Lifecycle Management System for MLDev and MLOps_](https://www.microsoft.com/en-us/research/publication/ease-ml-a-lifecycle-management-system-for-mldev-and-mlops/), **CIDR'21*.
- [**Ease.ML/DocParser**](https://github.com/DS3Lab/DocParser) <img width="50px" src="https://img.shields.io/github/stars/DS3Lab/DocParser.svg">  Data Parsing and Ingestion 
  - :Main Reference: [_DocParser: Hierarchical Structure Parsing of Document Renderings_](https://arxiv.org/abs/1911.01702), **AAAI'19**.
- [**Ease.ML/Snoopy**](https://github.com/easeml/snoopy) <img width="50px" src="https://img.shields.io/github/stars/easeml/snoopy.svg">  Automatic Feasibility Study for ML
  - Main Reference: [_Automatic Feasibility Study via Data Quality Analysis for ML: A Case-Study on Label Noise_](https://arxiv.org/abs/2010.08410), **ICDE'22**.
- [**Ease.ML/DataScope**](https://github.com/easeml/datascope) <img width="50px" src="https://img.shields.io/github/stars/easeml/datascope.svg">  Data Valuation and Debugging for ML
  - Main Reference: [_Data Debugging with Shapley Importance over End-to-End Machine Learning Pipelines_](https://arxiv.org/abs/2204.11131?context=cs.DB)
- [**Ease.ML/AutoML**](https://github.com/easeml/automl) <img width="50px" src="https://img.shields.io/github/stars/easeml/automl.svg"> Multi-tenant AutoML 
  - Main Reference: [_Ease.ml: towards multi-tenant resource sharing for machine learning workloads_](https://arxiv.org/abs/1708.07308), **VLDB'17**.
- [**Ease.ML/CI**](https://github.com/easeml/ci) <img width="50px" src="https://img.shields.io/github/stars/easeml/ci.svg">  Rigorous Testing and CI/CD for ML 
  - Main Reference: [_Continuous Integration of Machine Learning Models with ease.ml/ci: Towards a Rigorous Yet Practical Treatment_](https://arxiv.org/abs/1903.00278), **SysML'19*.
- [**Ease.ML/ModelPicker**](https://github.com/easeml/modelpicker) <img width="50px" src="https://img.shields.io/github/stars/easeml/modelpicker.svg">  Data-Efficient Continuous A/B Testing for ML 
  - Main Reference: [_Online Active Model Selection for Pre-trained Classifiers_](https://arxiv.org/abs/2010.09818), **AISTATS'21**.

