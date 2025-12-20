---
layout: posterpage
categories: [poster]
posternumber: P05
speaker: Dr. Miguel Gallegos
location: 'University of Luxembourg · Department of Physics and Materials Science · Luxembourg (LU)'
title: 'ChemDBX: Building, Indexing, and Exploring Chemical Spaces for Molecular Discovery'
authors: 'M. Gallegos, A. Tkatchenko'
abstract: [
"The systematic exploration of Chemical Compound Space (CCS) has become a cornerstone of modern chem-
istry, driven by the rapid growth of machine learning (ML) approaches. The emergence of large-scale chemical
datasets such as GDB17, (1) QCML, (2) or OMol25, (3) to name a few, has opened unprecedented opportunities
to uncover structure–property relationships and design novel molecules across chemistry, materials science, and
drug discovery. Yet, this abundance also poses challenges: many datasets lack transparent generation protocols,
internal consistency, or comprehensive information about their chemical coverage, a nontrivial issue given the
multidimensional nature of chemical space. Beyond elemental composition and topology, meaningful coverage
must also capture additional factors such as conformational diversity (e.g., equilibrium vs. reactive geometries)
and the inclusion of uni- and multimolecular systems, among others. As a result, redundancies and biases
often arise, obscuring chemical logic and hindering the assessment of model transferability and performance,
ultimately limiting data-driven discovery.

In this work, we introduce ChemDBX, a computational platform for the systematic construction, indexing,
and exploration of molecular databases. ChemDBX imports existing datasets in XYZ or HDF5 format, auto-
matically indexes and deduplicates entries, and characterizes their elemental composition, molecular formula,
and aggregation degree. It performs hierarchical structural classification and conformational clustering to map
regions of CCS and evaluate dataset diversity. Beyond indexing, ChemDBX computes local geometrical and
chemical descriptors-including functional groups and atomic environments-providing a multiscale view that
links molecules to their structural building blocks. For supramolecular systems, it applies graph-based decom-
position to identify components and supports user-defined functional classifications.

Finally, ChemDBX integrates molecular search tools, interactive analysis and visualization of molecular and
quantum-mechanical properties, and modules for tailor-made database generation through both top-down and
bottom-up strategies. Equipped with a graphical user interface (GUI) and a command-line interface (CLI), this
unified framework enables robust and transparent exploration of CCS, while supporting the informed creation
of novel databases aligned with active learning protocols."]
references: [
['L. Ruddigkeit; R. van Deursen; L. C. Blum; J. L. Reymond', 'Journal of Chemical Information and Modeling
2012', '52', '2864–2875'],
['S. Ganscha; O. T. Unke; D. Ahlin; H. Maennel; S. Kashubin; K. R. Müller', 'Scientific Data 2025', '12', '406'],
['D. S. Levine; M. Shuaibi; E. W. C. Spotte-Smith; M. G. Taylor; M. R. Hasyim; K. Michel; I. Batatia;
G. Csányi; M. Dzamba; P. Eastman; N. C. Frey; X. Fu; V. Gharakhanyan; A. S. Krishnapriyan; J. A.
Rackers; S. Raja; A. Rizvi; A. S. Rosen; Z. Ulissi; S. Vargas; C. L. Zitnick; S. M. Blau; B. M. Wood',
'The Open Molecules 2025 (OMol25) Dataset', 'Evaluations, and Models', '2025', 'https://arxiv.org/
abs/2505.08762']
]
---
