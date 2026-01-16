---
layout: posterpage
categories: [poster]
posternumber: P25
speaker: Aakash Ashok Naik
location: 'Bundesanstalt für Materialforschung und -prüfung · Department of Digital Materials Chemistry · Berlin (DE)'
title: "Do bonding descriptors help in machine learning material properties?"
authors: 'A. A. Naik, N. Dhamrait, K. Ueltzen, C. Ertural, P. Benner, G-M. Rignanese, J. George'
abstract: [
"The concept of the chemical bond has long served chemists in rationalizing material properties,[1]reaction pathways,[2] or crystal structure stability.[3,4] Despite several theoretical frameworks being developed over the years to characterize bonding in solid-state materials,[5–7] a comprehensive assessment of the impact of incorporating quantum chemical bonding descriptors into machine learning studies of material properties has remained elusive, partly due to the lack of data. To overcome this issue, a quantum-chemical bonding analysis workflow[8,9] was developed, enabling the high-throughput computation of orbital-based bonding descriptors derived from ab initio calculations. By utilizing this workflow, we have constructed a database of bonding descriptors for approximately 13,000 structures from the Materials Project. A total of 1,500 entries from this dataset have already been published as part of our initial database validation publication.[10,11] The LobsterPy[12] package developed alongside enabled the generation of summaries for the most important bonds in materials and provided tools to transform the raw bonding data from the database into machine learning-ready descriptors. The curated descriptors span different types, including statistical representations of bonding characteristics for traditional ML algorithms (e.g., random forests), textual descriptions for large language models (LLMs), and structure graphs for graph neural networks (GNNs). Here, we present the results from employing the statistical bonding descriptors in machine learning to predict the mechanical, vibrational, and thermal properties of crystalline materials. Through this work, we demonstrate that incorporating quantum chemical bonding-based descriptors alongside traditional composition and structure-based ones enhances the model performance. Using SISSO,[13] a symbolic regression method, we also demonstrate that one can discover simple, intuitive relationships between bonding and material properties on a larger scale, which was previously not possible."]
references: [
['J. B. Goodenough', 'John Wiley And Sons 1963'],
['R. B. Woodward; R. Hoffmann', 'J. Am. Chem. Soc. 1965', '87', '395–397'],
['V. M. Goldschmidt', 'Naturwissenschaften 1926', '14', '477–485'],
['L. Pauling', 'J. Am. Chem. Soc. 1929', '51', '1010–1026'],
['R. S. Mulliken', 'The Journal of Chemical Physics 1955', '23', '1833–1840'],
['R. F. W. Bader; T. T. Nguyen-Dang', 'Academic Press 1981', '63–124'],
['M. Raupach; R. Tonner', 'The Journal of Chemical Physics 2015', '142', '194105'],
['J. George; G. Petretto; A. A. Naik; M. Esters; A. J. Jackson; R. Nelson; R. Dronskowski; G. Rignanese; G. Hautier', 'ChemPlusChem 2022', '87', 'DOI:10.1002/cplu.202200123'],
['A. M. Ganose; H. Sahasrabuddhe; M. Asta; K. Beck; T. Biswas; A. Bonkowski; J. Bustamante; X. Chen; Y. Chiang; D. C. Chrzan; J. Clary; O. A. Cohen; C. Ertural; M. C. Gallant; J. George; S. Gerits; R. E. A. Goodall; R. D. Guha; G. Hautier; M. Horton; T. J. Inizan; A. D. Kaplan; R. S. Kingsbury; M. C. Kuner; B. Li; X. Linn; M. J. McDermott; R. S. Mohanakrishnan; A. N. Naik; J. B. Neaton; S. M. Parmar; K. A. Persson; G. Petretto; T. A. R. Purcell; F. Ricci; B. Rich; J. Riebesell; G.-M. Rignanese; A. S. Rosen; M. Scheffler; J. Schmidt; J.-X. Shen; A. Sobolev; R. Sundararaman; C. Tezak; V. Trinquet; J. B. Varley; D. Vigil-Fowler; D. Wang; D. Waroquiers; M. Wen; H. Yang; H. Zheng; J. Zheng; Z. Zhu; A. Jain', 'Digital Discovery 2025', '4', '1944–1973'],
['A. A. Naik; C. Ertural; N. Dhamrait; P. Benner; J. George', 'Materials Science 2023', 'DOI:10.48550/ARXIV.2304.02726'],
['A. A. Naik; C. Ertural; N. Dhamrait; P. Benner; J. George', '2023', 'DOI:10.5281/zenodo.8091844'],
['A. A. Naik; K. Ueltzen; C. Ertural; A. J. Jackson; J. George', 'Journal of Open Source Software 2024', '9', '6286'],
['R. Ouyang; S. Curtarolo; E. Ahmetcik; M. Scheffler; L. M. Ghiringhelli', 'Phys. Rev. Mater. 2018', '2', '083802']
]
---
