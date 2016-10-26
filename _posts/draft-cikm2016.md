---
layout: post
title: CIKM 2016
---

This blog post is the second in (a hopefully a long) series of posts that take a look at recent conference proceedings
and my favourite papers among them. I am a happy proceedings addict: I tend to read through all major proceedings of information
retrieval conferences and recently have also taken an interest in NLP/CV (read: deep learning) conferences - well, who hasn't? 

Here, I am going over the CIKM proceedings - the conference is currently ongoing with all papers already up on [ACM Portal](http://dl.acm.org/citation.cfm?id=2983323). My favourite long papers this year:

1. [*A deep relevance matching model for ad-hoc retrieval*](http://dx.doi.org/10.1145/2983323.2983769) is showing once more how much fiddling with the standard deep learning pipeline is necessary to improve ad-hoc retrieval over a BM25 baseline. The paper includes a great writeup on the difference of the matching problem as encountered in NLP (semantic matching - here deep learning out of the box yields good results) and IR (relevance matching - here deep learning out of the box battles to overcome the most basic baselines). After this great analysis and engineering effort, the authors' best deep learning approaches achieves a MAP of 0.113 on ClueWeb09B while BM25 manages a 0.100. The difference is a bit larger for Robust-04: BM25 yields a MAP of 0.253, the best deep learner reports back with 0.279. Still, we are a long way off from deep learning ruling the IR world.

2. Another deep learning paper that I include here for its less-than-mainstream application: [*A Neural Network Approach to Quote Recommendation in Writings*](http://dx.doi.org/10.1145/2983323.2983788). When writing papers (or increasingly grants) I'd love to have a "quote recommender" that just gives me a list of fitting quotes for my writing. This is exactly what the authors developed (with an LSTM to go deep). The dataset is derived from Project Gutenberg literature - all quotes from a predefined set of quotes found in those works are removed and treated as gold standard to predict. I wonder if a similar data set can be built from scientific papers and their usage of classic quotes.

3. 



