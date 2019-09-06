# Context and Compositionality in Biological and Artificial Neural Systems
#### [NeurIPS 2019](https://neurips.cc) Workshop, Vancouver, Canada
##### December 2019


## Introduction
The ability to integrate semantic information across narratives is fundamental to language understanding in both biological and artificial cognitive systems. In recent years, enormous strides have been made in NLP and Machine Learning to develop architectures and techniques that effectively capture these effects. The field has moved away from traditional bag-of-words approaches that ignore temporal ordering, and instead embraced RNNs [1][2][3][4], Temporal CNNs [5] and Transformers [6], which incorporate contextual information at varying timescales. While these architectures have lead to state-of-the-art performance on many difficult language understanding tasks [7],[8], it is unclear what representations these networks learn and how exactly they incorporate context. Interpreting these networks, systematically analyzing the advantages and disadvantages of different elements, such as gating or attention, and reflecting on the capacity of the networks across various timescales are open and important questions. 

On the biological side, recent work in neuroscience suggests that areas in the brain are organized into a temporal hierarchy in which different areas are not only sensitive to specific semantic information [9] but also to the composition of information at different timescales [10][11]. Computational neuroscience has moved in the direction of leveraging deep learning to gain insights about the brain [12][13]. By answering questions on the underlying mechanisms and representational interpretability of these artificial networks, we can also expand our understanding of temporal hierarchies, memory, and capacity effects in the brain.  

In this workshop we aim to bring together researchers from machine learning, NLP, and neuroscience to explore and discuss how computational models should effectively capture the multi-timescale, context-dependent effects that seem essential for processes such as language understanding. We believe that this will lead to both a deeper understanding of biological language systems, as well as improved artificial systems that leverage these insights to better understand language.


## Important Dates

|---
| Name | Date 
|:------ |:------ 
| Paper Submission Deadline | Update: September 13th, 2019 ~~September 9th, 2019~~ 
| Final Decisions | September 29th, 2019
| Workshop Date | December 13th or 14th, 2019

## Call for Papers
Submit at: [https://cmt3.research.microsoft.com/CNTXTCOMP2019/](https://cmt3.research.microsoft.com/CNTXTCOMP2019/)

We will consider the following (non-exhaustive) list of topics for contribution:
- Contextual sequence processing in the human brain
- Compositional representations in the human brain
- Systematic generalization in deep learning
- Compositionality in human intelligence
- Compositionality in natural language
- Understanding composition and temporal processing in neural network models
- New approaches to compositionality and temporal processing in language
- Hierarchical representations of temporal information
- Datasets for contextual sequence processing
- Applications of compositional neural networks to real-world problems

**Formatting Instructions:**  All submissions must be in PDF format. Submissions are limited to four content pages, including all figures and tables; additional pages containing only references are allowed. You must format your submission using the [NeurIPS 2019 LaTeX style file](https://neurips.cc/Conferences/2019/PaperInformation/StyleFiles). Submissions that violate the NeurIPS style (e.g., by decreasing margins or font sizes) or page limits may be rejected without further review. All submissions should be anonymous.

Accepted papers will be presented during a poster session, with spotlight oral presentations for exceptional submissions. The accepted papers will be made publicly available as non-archival reports, allowing future submissions to archival conferences or journals.

The review process is double-blind. We also welcome published papers that are within the scope of the workshop (without re-formatting, if the paper is already 4 pages or shorter). Already-published papers do not have to be anonymous. They are eligible for poster sessions and will only have a very light review process.
Please redirect questions and all future correspondence to [shaileejain@utexas.edu](mailto:shaileejain@utexas.edu).


## Schedule

## Invited Speakers

- [Prof. Yoshua Bengio](https://mila.quebec/en/yoshua-bengio/), MILA - University of Montreal
- [Prof. Patricia Churchland](https://patriciachurchland.com/), University of California San Diego
- [Prof. Liina Pylkkänen](https://wp.nyu.edu/neurolinglab/people/liina-pylkkanen/), New York University
- [Prof. Gina Kuperberg](https://projects.iq.harvard.edu/kuperberglab/people/gina-r-kuperberg), Tufts University and Massachusetts General Hospital
- [Prof. Tom Mitchell](http://www.cs.cmu.edu/~tom/), Carnegie Mellon University
- [Prof. Evelina Fedorenko](https://evlab.mit.edu), MIT
- [Prof. Paul Smolensky](https://www.microsoft.com/en-us/research/people/psmo/), Johns Hopkins University and Microsoft Research
- [Prof. Gary Marcus](http://garymarcus.com), New York University and Robust.AI
- [Kenton Lee](https://kentonl.com), Google

## Organizers

- Javier Turek, Intel Labs
- Alex Huth, The University of Texas at Austin
- Shailee Jain, The University of Texas at Austin
- Chris Honey, Johns Hopkins University
- Tal Linzen, Johns Hopkins University
- Alan Yuille, Johns Hopkins University
- Emma Strubell, Carnegie Mellon University
- Kyunghyun Cho, Facebook and New York University
- Leila Wehbe, Carnegie Mellon University

## Sponsors

## References
1. S. Hochreiter and J. Schmidhuber. Long short-term memory. Neural Comput., 9(8):1735–1780, Nov. 1997.
2. J. Chung, C. Gulcehre, K. Cho, and Y. Bengio. Gated feedback recurrent neural networks. Proceedings of the 32nd International Conference on Machine Learning, volume 37 of Proceedings of Machine Learning Research, pages 2067–2075, Lille, France, 07–09 Jul 2015.
3. S. Chandar, C. Sankar, E. Vorontsov, S. E. Kahou, and Y. Bengio.  Towards non-saturatingrecurrent units for modelling long-term dependencies.arXiv preprint arXiv:1902.06704, 2019.
4. J. Chung, S. Ahn, and Y. Bengio. Hierarchical multiscale recurrent neural networks. In ICLR, 2017.
5. S. Bai, J. Z. Kolter, and V. Koltun.   An empirical evaluation of generic convolutional andrecurrent networks for sequence modeling.CoRR, abs/1803.01271, 2018.
6. A. Vaswani, N. Shazeer, N. Parmar, J. Uszkoreit, L. Jones, A. N. Gomez, L. u. Kaiser, andI. Polosukhin. Attention is all you need. In I. Guyon, U. V. Luxburg, S. Bengio, H. Wallach,R. Fergus, S. Vishwanathan, and R. Garnett, editors,Advances in Neural Information ProcessingSystems 30, pages 5998–6008. Curran Associates, Inc., 2017.
7. M. Peters, M. Neumann, M. Iyyer, M. Gardner, C. Clark, K. Lee, and L. Zettlemoyer.  Deepcontextualized word representations. InProceedings of the 2018 Conference of the North Amer-ican Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long Papers), pages 2227–2237, New Orleans, Louisiana, June 2018. Association for Computational Linguistics.
8. J. Devlin, M. Chang, K. Lee, and K. Toutanova.  BERT: pre-training of deep bidirectionaltransformers for language understanding.CoRR, abs/1810.04805, 2018.
9. A. G. Huth, W. A. de Heer, T. L. Griffiths, F. E. Theunissen, and J. L. Gallant. Natural speech reveals the semantic maps that tile human cerebral cortex. Nature, 532(7600):453–458, 2016.
10. C. Baldassano, J. Chen, A. Zadbood, J. W. Pillow, U. Hasson, and K. A. Norman. Discovering event structure in continuous narrative perception and memory. Neuron, 95(3):709 – 721.e5,2017.
11. K. D. Himberger, H.-Y. Chien, and C. J. Honey. Principles of temporal processing across thecortical hierarchy. Neuroscience, 389:161 – 174, 2018.  Sensory Sequence Processing in the Brain.
12. L. Wehbe, A. Vaswani, K. Knight, and T. Mitchell.  Aligning context-based statistical models of language with brain activity during reading. In EMNLP, 2014.
13. S. Jain and A. Huth. Incorporating context into language encoding models for fmri. In Advances in Neural Information Processing Systems 31, pages 6628–6637, 2018.
14. Y. Lerner, C. J. Honey, L. J. Silbert, and U. Hasson. Topographic Mapping of a Hierarchy of Temporal Receptive Windows Using a Narrated Story. Journal of Neuroscience 23 February 2011, 31 (8) 2906-2915.
