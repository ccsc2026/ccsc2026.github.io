---
layout: posterpage
categories: [poster]
posternumber: P37
speaker: Deqi Tang
location: 'University of Zurich · Department of Chemistry · Zurich (CH)'
title: "Bridging Dynamics and Design in Molecular Water Oxidation: Enhanced sampling and Machine-Learned Collective Variables"
authors: 'D. Tang, R. Ketkaew, F. Creazzo, S. Luber'
abstract: [
"Enhanced sampling methods, paired with high-performance density functional theory molecular dynamics (DFT-MD), allow us to study rare events in catalytic reactions, while including explicitly the solvent effects. This provides exciting perspectives on catalyst design.
Ruthenium-based water oxidation catalysts (WOCs) incorporating the 2,2'-bipyridine-6,6'-dicarboxylate (bda) ligand[1] have become a pivotal platform in the development of efficient catalysts for the oxygen evolution reaction (OER). However, the mechanistic intricacies of OER remain elusive. As already shown extensively e.g. in previous work of the group[2-6], explicit solvation (using periodic boundary conditions) in combination with dynamics and enhanced sampling are indispensable to explore the reaction mechanism of homogeneous and heterogeneous WOCs in a realistic, sophisticated manner. Here, we employ DFT-MD and metadynamics to unravel structural and dynamical properties of the water network around Ru(bda)-based WOCs with a focus on clarifying mechanisms in catalyzing the water nucleophilic attack (WNA), revealing details on reaction mechanisms such as Ru-oxo formation and proton transfer. Our findings uncover a seven-coordinate Ru geometry stabilizing a dynamic water network, enabling an efficient WNA. Leveraging insights from metadynamics, we engineered a new catalyst by modifying the bipyridine ligand, aiming to tune the WNA mechanism and achieve a lower free-energy barrier. These results highlight robust hydrogen-bond acceptors and confined microscopic environments as key design criteria for engineering high-performance Ru(bda)-based WOCs.
Crucial parameters in such simulations are the so-called collective variables (CVs), which are usually selected based on chemical intuition and thus biased and not universally transferrable to other systems. We have therefore developed a deep autoencoder neural network (DAENN) for discovering general purpose CVs[7]. The developed autoencoder is capable of searching for hidden CVs in expanded configuration space automatically. To help other people to use the DAENN algorithm, we have developed the open-source DeepCV package[8]."]
references: [
['N. Noll; A. M. Krause; F. Beuerle; F. Würthner', 'Nat. Catal 2022', '5 (10)', '867–877'],
['M. Schilling; R. A. Cunha; S. Luber', 'J. Chem. Theory Comput. 2020', '16 (4)', '2436–2449'],
['M. Schilling; R. A. Cunha; S. Luber', 'ACS Catal. 2020', '10', '14', '7657–7667'],
['R. Ketkaew; F. Creazzo; K. Sivula; S. Luber', 'Chem. Cat. 2024', '4 (9)', '101085'],
['F. H. Hodel; P. Deglmann; S. Luber', 'J. Chem. Theory Comput. 2017', '13 (7)', '3348–3358'],
['F. Creazzo; R. Ketkaew; K. Sivula; S. Luber', 'Appl. Surf. Sci. 2022', '601', '154203'],
['R. Ketkaew; F. Creazzo; S. Luber', 'J. Phys. Chem. Lett. 2022', '13 (7)', '1797–1805'],
['R. Ketkaew; S. Luber', 'J. Chem. Inf. Model. 2022', '62 (24)', '6352–6364']
]
---
