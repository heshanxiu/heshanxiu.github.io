---
layout: archive
title: "Research Projects"
permalink: /projects/
author_profile: true
---

Here are some of my selected research projects. There are three parts: [Knowledge-Enhanced NLP](#knowledge-enhanced-nlp), 
[Machine Commonsense](#machine-commonsense), and [Graphs](#graphs)

## Knowledge-Enhanced NLP

## 1. Goal-Oriented Event Chain Generation

Implemented three large language models (GPT2, T5 and BART) to perform event chain sequences generation. 
On average, the models outperformed the state-of-the-art statistical baseline by 3% on E-ROUGE scores. 
Proved the generated event sequences helpful to text generation domain in a zero-shot setting.

## 2. On the Difficulty of Utilizing Commonsense Knowledge

Investigated the difficulties to ground commonsense knowledge in databases, such as ATOMIC and ASER. 
After showing the severity of finding useful information, improved the performance in SocialIQA, 
a social event dataset, with a trainable retriever.

[Report: On the Difficulty of Utilizing Commonsense Knowledge](/files/Trainable_Retriever.pdf)

## 3. Graph Transformer

Implemented Graph-Transformer architecture to represent edge level information as positional encodings to graphs. 
Developed strategies for Graph-Transformer such as connectivity and eigenvalue similarity. 
Initial results achieved 0.77 ROCAUC score on validation time.

## Machine Commonsense


## 1. Grounded Situation Recognition with Vision and Language Models

Targeted Grounded Situation Recognition (SWiG datasets) with two types of Vision and Language Models. 
CLIP-based model exceeded traditional computer vision models. Traditional Vision and Language approach matches previous 
baselines on noun predictions with 63.33\% accuracy given ground truth verb.

[Report: Grounded Situation Recognition with VL Models](/files/Grounded%20Situation%20Recognition.pdf)

## 2. Probing Vision and Language Models 

<img style="float: right;" src="/images/probing_vl_models.png" width="200">

Examined additional cross attention layers in LXMERT. Extracted visual and text hidden representations to
 perform visual Semantic Role Labeling. Concluded concluded the additional layers might not always be beneficial. 
 
[Report: Probing Vision and Language Models ](/files/Trainable_Retriever.pdf)

## 3. Stacked Attention Models
 
Formulated VQA models based on CNN+BILSTM+SAN network with Tensorflow. 
The model outperformed counterparts by 5% test time accuracy with DAQUAR, 
COCO-QA and VQA datasets.
 
 
## Graphs
 
## 1. GNN Adversarial Training
 
While GNNs are susceptible to adversarial attacks, we design mechanisms to perturb edge connections for GNN representations.
  The perturbed models beat traditional adversarial approach in performances both on clean accuracy and adversarial accuracy.

[Report: GNN Adversarial Training](/files/GNN_ADV_Train.pdf)