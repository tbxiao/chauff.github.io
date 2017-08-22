---
layout: post
title: ACL 2017 - A readthrough
thumbnail: "/img/og_sigir2017.png" 
---

[ACL 2017](http://acl2017.org/) with its nearly 200 full papers and more than 100 short papers was a treasure trove again for inspiring approaches, problems and datasets. There is really only one topic I stay away from and that is parsing - it just does not hold a lot of interest for me. Here are the papers I found most interesting this year:

* [*FOIL it! Find One mismatch between Image and Language caption*](http://aclweb.org/anthology/P/P17/P17-1024.pdf) takes a closer look at visual question answering (given an image an a question, generate an answer) and image captioning approaches (given an image, generate a caption) by creating a **diagnostic dataset** based on the [MS-COCO](http://mscoco.org/) benchmark. MS-COCO contains 300K images, each with five(+) different captions, written by crowd workers. Image captioning approaches achieve great results on this benchmark, but do they truly learn how to caption or do they exploit biases in the dataset? This diagnostic dataset provides more than a few hints that it is the latter. The authors take the MS-COCO image/caption pairs as their starting point and introduce a single error (a semantically related but incorrect term) into each caption; as an example, the true caption *Three bicycle riders, some trees and a pigeon.* for an image becomes the foiled caption *Three motorcycle riders, some trees and a pigeon.* An image captioning approach taking  They then adapt state-of-the-art image captioning and visual question answering approaches for the tasks of caption classification (correct/foil), foil word detection and foil word correction. These state-of-the-art algorithms are not doing too well at detecting foil captions (at most an accuracy of 45.44 compared to 94.52 that a majority vote of humans achieves), indicating that there is still a long way to go. I really like the idea of a diagnostic dataset, something that we have not yet picked up on a lot in IR.

* 
