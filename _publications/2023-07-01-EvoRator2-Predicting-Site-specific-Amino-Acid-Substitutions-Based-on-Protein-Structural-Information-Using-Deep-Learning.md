---
title: "EvoRator2: Predicting Site-specific Amino Acid Substitutions Based on Protein Structural Information Using Deep Learning"
collection: publications
permalink: /publication/2023-07-01-EvoRator2-Predicting-Site-specific-Amino-Acid-Substitutions-Based-on-Protein-Structural-Information-Using-Deep-Learning
date: 2023-07-01
venue: 'Journal of Molecular Biology'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0022283623002401'
paperpdf: '/files/Nagar et al. - 2023 - EvoRator2 Predicting Site-specific Amino Acid Sub.pdf'
citation: ' Natan Nagar,  Jérôme Tubiana,  Gil Loewenthal,  Haim Wolfson,  Nir Ben,  Tal Pupko, &quot;EvoRator2: Predicting Site-specific Amino Acid Substitutions Based on Protein Structural Information Using Deep Learning.&quot; Journal of Molecular Biology, 2023.'
---
<b> Abstract: </b>Multiple sequence alignments (MSAs) are the workhorse of molecular evolution and structural biology research. From MSAs, the amino acids that are tolerated at each site during protein evolution can be inferred. However, little is known regarding the repertoire of tolerated amino acids in proteins when only a few or no sequence homologs are available, such as orphan and de novo designed proteins. Here we present EvoRator2, a deep-learning algorithm trained on over 15,000 protein structures that can predict which amino acids are tolerated at any given site, based exclusively on protein structural information mined from atomic coordinate files. We show that EvoRator2 obtained satisfying results for the prediction of position-weighted scoring matrices (PSSM). We further show that EvoRator2 obtained near state-of-the-art performance on proteins with high quality structures in predicting the effect of mutations in deep mutation scanning (DMS) experiments and that for certain DMS targets, EvoRator2 outperformed state-of-the-art methods. We also show that by combining EvoRator2′s predictions with those obtained by a state-of-the-art deep-learning method that accounts for the information in the MSA, the prediction of the effect of mutation in DMS experiments was improved in terms of both accuracy and stability. EvoRator2 is designed to predict which amino-acid substitutions are tolerated in such proteins without many homologous sequences, including orphan or de novo designed proteins. We implemented our approach in the EvoRator web server (https://evorator.tau.ac.il).