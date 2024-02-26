---
layout: category
title: Projects
category: projects
permalink: /projects
---

Over the past years, I have explored a large range of topics spanning attractor dynamics in working memory, computational psychiatry, novel dimensionality reduction techniques, and dynamical models of motor behavior. What all of these projects have in common is a strong focus on bridging brain activity with cognition and obervable behavior. 


### Dimensionality reduction beyond neural subspaces

How do we relate activity at the neural population level to behavior? While ever larger recordings have become possible over recent years,  it is central to extract low-dimensional structure in this activity in order to test hypotheses about circuit computation in this data. 
A central tool for this inquiry are dimensionality reduction methods, which identify the most relevant sources of variability in high-dimensional datasets. A basic principle of these methods is the identification of a neural subspace, consisting of a few “latent” dimensions that capture dominant activity patterns, which are often correlated across neurons. The interpretation of low-dimensional neural dynamics is significantly easier than interpreting single-neuron firing patterns in hundreds of neurons, allowing us to hypothesize about single- and multi-area network computations in relation to behavior and to the external world. 

In my  postdoc, I studied other relevant classes of covariability in large-scale neural recordings. In particular, in tasks with trial structure, data can be correlated over trials, neurons, or time (rather than just over neurons). Variability in each of these classes can be indicative of the computations performed by a neural population. In this project, we propose a novel, tensor-based dimensionality reduction technique that uncovers different covariability patterns, including neural sequences, trial-to-trial variability in neural firing latencies, and drifting neural subspaces (as is representational drift).

Pellegrino, A.\*, Stein, H.\*, Cayco Gajic, N.A. Mixed classes of covariability in neural data. Nature Neuroscience (in press).


### Discontinuities in working memory in anti-NMDAR encephalitis and schizophrenia

In my PhD, I studied NMDA receptor related working memory alterations in human patient populations. The goal was to test predictions from biophysical models of the prefrontal cortex, stating that NMDAR dysfunction should lead to altered attractor dynamics prefrontal activity. As a result, working memory performance should be impaired in patients with NMDAR dysfunction. 

In behavioral and EEG experiments in patients with autoimmune NMDAR dysfunction and schizophrenia, we could not confirm these model predictions, showing that active memory maintenance was intact. In contrast, we found a more subtle, but systematic effect on trial history biases: Patients showed a striking discontinuity between temporally adjacent memories that stands in stark contrast to attractive memory biases observed in neurotypical subjects. Decoding memory contents from EEG, we found that this reduction in serial dependence was reflected in less continuous memory codes spanning subsequent trials. With biophysical network models, we showed how this effect could be explained by reductions in short-term plasticity in patients with NMDAR dysfunction. 


Stein, H.\*, Barbosa, J.\*, et al. Reduced serial dependence suggests deficits in synaptic potentiation in antiNMDAR encephalitis and schizophrenia. Nature Communications 11, 4250 (2020).

Stein, H.\*, Barbosa, J.\*, & Compte, A. Towards biologically constrained attractor models of schizophrenia. Current Opinion in Neurobiology 70, 163-170 (2021).

Guasp, M., et al. Clinical characterization of patients in the post-acute stage of antiNMDA receptor encephalitis: a prospective observational cohort study and comparison with patients with schizophrenia spectrum disorders. The Lancet Neurology 21, 899-910, (2022).

Stein, H., et al. A. Neural signatures of reduced serial dependence in antiNMDAR encephalitis and schizophrenia. PsyArXiv (2024).

### Activity- and plasticity-based mechanisms of working memory

In a second, related PhD project, I studied the neural basis of trial history biases in a study across human subjects and non-human primates. Based on behavior, EEG and single-neuron recordings, we established links between working memory codes in neural activity, synaptic traces of previous memories, and trial history biases in memory reports.

We addressed a long-standing debate in the working memory field that concerns the nature of working memory codes: On the one hand, classic experimental and theoretical work has established that persistent, stimulus-tuned prefrontal activity can hold memories throughout short delays. On the other hand, more recent work claims that working memories can be held synaptically, without persistent activity. Our study showed that working memory is indeed actively encoded throughout memory delays, but as a result of that activity leaves a long-lived synaptic trace. Reactivations from this trace can occur during the inter-trial interval and gradually bias memories in the upcoming trial towards previous memory contents.

Barbosa, J.\*, Stein, H.\*, et al. Interplay between persistent activity and activity-silent dynamics in the prefrontal cortex underlies serial biases in working memory. Nature Neuroscience 23, 1016–1024 (2020).
