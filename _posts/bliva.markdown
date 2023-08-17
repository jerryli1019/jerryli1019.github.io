---
layout: post
image: /pdfs/bliva.pdf
venue: "Under Review AAAI 2024"
title:  "BLIVA: A Simple Multimodal LLM for Better Handling of Text-Rich Visual Questions"
authors: "Wenbo Hu*, Yifan Xu*, <strong>Yi Li</strong>, Weiyue Li, Zeyuan Chen, Zhuowen Tu"
date:   2023-08-15 00:00:00 +00:00
code: https://github.com/gordonhu608/Revisit_CLIP
website: https://gordonhu608.github.io/Revisit_CLIP/
arxiv: https://gordonhu608.github.io/Revisit_CLIP/
categories: research
---
We introduces BLIVA, an augmented version of InstructBLIP with 
Visual Assistant. BLIVA incorporates the query embeddings from 
InstructBLIP and also directly projects encoded patch embeddings 
into the LLM, a technique inspired by LLaVA. This approach ensures that
the model captures intricate details potentially missed during the query 
decoding process. Empirical evidence demonstrates that our model, BLIVA, 
significantly enhances performance in processing text-rich VQA benchmarks (up to
17.76% in OCR-VQA benchmark) and in undertaking typical VQA benchmarks 
(up to 7.9% in Visual Spatial Reasoning benchmark), comparing to our baseline 
InstructBLIP. BLIVA demonstrates significant capability in decoding realworld images, 
irrespective of text presence.