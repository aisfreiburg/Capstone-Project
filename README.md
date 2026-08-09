<img width="6050" height="334" alt="image" src="https://github.com/user-attachments/assets/dacfb4ab-43a4-4f13-822a-d7a090e0f927" />A Bioinformatic Approach of Lily-of-the-valley (Convallaria majalis) as an Anticancer Drug Candidate Against Oral Squamous Cell Carcinoma

Oral squamous cell carcinoma (OSCC) is the most prevalent malignancy in dentistry comprises about 90%. The current existing treament options such as chemotherapy, surgery, and radiotherapy lead to several adverse effects including the risk of metastasis, high toxicity against normal cells, and potential to drug escape mechanism. OSCC has distinct anatomical hierarchies that provide higher chance to undergo structural modifications upon treatments, making treatments become challenging. Thus, novel treatment discovery is needed to provide better options for combating OSCC with less negative effects. 
Lily-of-the-valley (Convallaria majalis) is one of the most popular flowers in the world. Originating in Europe, lily-of-the-valley has been widely known for the distinct floral aroma used in parfume manufactures, especially by extracting essential oils provided in the flowers. Nevertheless, this flower is famous for its toxicity if consumed directly, particularly due to the huge content of glycosides that alter heart functions. In contrast to this, several literature stated the potential of lily-of-the-valley derivatives to exert anticancer propertes. This project aimed to assess anticancer potential of this flower in against OSCC.

<img width="567" height="851" alt="lily2" src="https://github.com/user-attachments/assets/e6711efe-8338-4814-a7e8-81632091a287" />

Figure 1. Lily-of-the-valley.

About 29 compounds were obtained from lily-of-the-valley through literature, including convallatoxin, convalloside, convallatoxol, quercetin, kaempferol, lokundjoside, desglucocheirotoxin, benzyl alcohol, (Z)-3-hexen-1-ol, citronellol, geraniol, (Z)-3-hexenyl acetate, geranyl acetate, phenylacetonitrile, farnesol, nerol. geranial, benzyl acetate, 2,3-dihydrofarnesol, phenethyl alcohol, (E)-2-hexenal, octanol, nonanal, decanal, neral, convallasaponin A, spirostanol lycotetroside, furostanol lycotetroside, and phenylacetonitrile. The SMILES codes were provided by PubChem databases, but both spirostanol lycotetroside and furostanol lycotetroside did not have the codes due to their novel discovery, thus both were excluded from this project. Compound targets were assessed through SwissTargetPrediction, resulting in 656 target proteins. On the other hand, OSCC-related genes were gained through OMIM and DisGeNet databases by inserting keywords “oral squamous cell carcinoma” in OMIM and “oral squamous carcinoma” in DisGeNet, leading to 4295 target genes. Furthermore, analysis of overlapping proteins using Venny platform resulted in 42 genes (0,8%) as shown by Figure 2. 

<img width="1280" height="1280" alt="venny-oscc lily" src="https://github.com/user-attachments/assets/6cad0ac8-6810-4284-b471-59774c284dba" />

Figure 2. Analysis of overlapping proteins using Venny resulted in 42 proteins (0.8%).

Further analysis using Cytoscape was undergone to provide protein-to-protein interaction (PPI) network visualisation of combined genes through STRING features by importing network from public database, then inserting the whole proteins as shown by Figure 3. In this process, further analysis to reveal the most significant proteins based on degree ran and resulted in top 19 overlapping proteins, then they were reduced to 15 proteins only. This process was also run simultaneously in STRING database by inserting only the overlapping genes due to database limitation of processing <2000 proteins. These steps revealed that ESR1 might play dominant interaction in this scenario due its highest degree score of 6.0.

<img width="1278" height="908" alt="lily-compound csv" src="https://github.com/user-attachments/assets/ebf7fc36-8fe4-4a1f-950e-29f2a55fb69e" />

Figure 3. Network visualisation comprising combined genes. 

<img width="344" height="363" alt="table 1_oscc" src="https://github.com/user-attachments/assets/55d521f0-3e3b-4bf6-ac27-1a0b7bc117b8" />

Table 1. List of overlapping genes based on degree revealed that ESR1 might play dominant interaction in this simulation.

Moreover, analysis of compound targets of lily-of-the-valley were performed in Cytoscape and formed a network of Figure 4. Enrichment analysis of KEGG and gene ontology (biological process and molecular function) were performed to understand further functions and possible explanations of the overlapping proteins. These processes were performed in STRING database and ShinyGo. KEGG and gene ontology analysis, particularly molecular function analysis, highlighted the prominent roles of the proteins to work on nitrogen metabolism and carbonate dehydratase activity that managed pH of the cells, confirming that OSCC frequently modified tumor microenvironments and maximised its metabolism to increase their surveillance. On the other hand, biological process analysis showed interesting data as it highlighted the origin of the overlapping proteins might be due to toxic substance response. This supported the evidence that the epithelial-to-mesenchymal transition (EMT) of OSCC arised from continuous genetic mutations from toxic subtance exposures, such as betel nut chewing, alcohol consumption, or smoking. Finally, network pharmacology was formed by merging the KEGG network, compound targets, and STRING analysis of the overlapping genes. This process highlighted the prominent roles of phenylacetonitrile among other compounds to regulate multiple protein targets as shown by Figure 10 . 

<img width="1334" height="830" alt="string_interactions_short (3) tsv" src="https://github.com/user-attachments/assets/506ee8a7-301d-46a4-a275-ce6ff4c6c2f8" />

Figure 4. PPI network of overlapping genes using STRING database.

<img width="1334" height="830" alt="KGGOSCCLILY csv_2" src="https://github.com/user-attachments/assets/a6d198b9-02be-4ecc-a288-e8208465d479" />

Figure 5. KEGG network of the overlapping genes.

<img width="1278" height="908" alt="lily-compound csv" src="https://github.com/user-attachments/assets/d7231e82-f896-40f1-93bb-44098fe92131" />

Figure 6. Lily-of-the-valley compound targets visualisation using Cytoscape.

<img width="5274" height="2946" alt="enrichment_KEGG_sim0 8_graph" src="https://github.com/user-attachments/assets/cdb36f4a-6b46-4595-ad6f-bde339f054bc" />

Figure 7. KEGG analysis highlighted the pathways associated with overlapping proteins that was dominated by altering nitrogen metabolism. 

<img width="5274" height="2946" alt="enrichment_Function_sim0 8_graph" src="https://github.com/user-attachments/assets/c3b83cce-2522-412e-882a-66c18bdcacd6" />

Figure 8. Molecular function enrichment analysis revealed the prominent roles of the proteins functioned in carbonate dehydratase activity.

<img width="5274" height="2946" alt="enrichment_Process_sim0 8_graph" src="https://github.com/user-attachments/assets/633fe6ba-fd4b-4fca-b03f-eef45b2b6eaf" />

Figure 9. Biological process analysis showed that the overlapping proteins might be the response to toxic substance, supporting the evidence of OSCC etiology of exposure to toxic substances to initiate carcinogenesis. 

<img width="1334" height="830" alt="Merged Network_3(11111)" src="https://github.com/user-attachments/assets/d74e9e8e-5dac-4048-ab7f-91f8f66c834a" />

Figure 10. Network pharmacology highlighted the prominent interactions by phenylacetonitrile against multiple protein targets.

Molecular docking simulation was performed to identify the interaction between phenylacetonitrile and OSCC-related genes. In this step, 3 proteins were chosen based on the different degree scores, including ESR 1 (degree score: 6.0), EGFR (degree score: 2.0), and GSK3B (degree score: 1.0). In this part, target proteins were chosen based on data provided by UniProt and confirmed through the RCSB PDB database. The SMILES code of phenylacetonitrile was obtained from PubChem.

<img width="619" height="166" alt="table 2" src="https://github.com/user-attachments/assets/4df7f578-fe7c-4b5c-8128-eefa15a589af" />

Table 2. Information about ligand and target proteins for molecular docking.

Docking simulation was undergone in SwissDock platform. In this step, AutoDock Vina docking was chosen, then the SMILES code of phenylacetonitrile was inserted in ligand section. In target section, the PDB ID of ESR1, EGFR, and GSK3B were inserted consecutively in the target sections and the coordinates were set according to PrankWeb analysis. Then, the “search box size” was set to 20 Å for each section.  For the last step, sampling exhaustivity was set to 4. Finally, molecular docking simulation was performed.

<img width="936" height="623" alt="ESR1-docking" src="https://github.com/user-attachments/assets/49a93b27-d797-49b4-aca4-d326d28768ef" />
<img width="453" height="540" alt="ESR1-affinity" src="https://github.com/user-attachments/assets/0d7d0086-d9c7-4a3d-b77e-eec90eb22eb6" />

Figure 11. Docking simulation of ESR1 (7RS7) and phenylacetonitrile showed model 1 possessed the highest affinity energy by scoring -5,120 kcal/mol.

<img width="903" height="615" alt="EGFR-docking" src="https://github.com/user-attachments/assets/a1607496-27a4-4577-92ad-0e3cc7469480" />
<img width="446" height="556" alt="EGFR-affinity" src="https://github.com/user-attachments/assets/69058b14-d885-4cb7-907c-00352d713508" />

Figure 12. Docking simulation of EGFR (4ZSE) and phenylacetonitrile showed model 1 possessed the highest affinity energy by scoring -3,990 kcal/mol.

<img width="878" height="620" alt="GSK3B-docking" src="https://github.com/user-attachments/assets/d112068e-e40a-46e3-83de-839523327dc1" />
<img width="447" height="553" alt="GSK3B-affinity" src="https://github.com/user-attachments/assets/b804dba5-006c-4e18-9142-f31196b1b80a" />

Figure 13. Docking simulation of GSK3B (1J1B) and phenylacetonitrile showed model 1 possessed the highest affinity energy by scoring -4,423 kcal/mol.

In this section, the highest binding affinity of ESR1 (7RS7), EGFR (4ZSE), and GSK3B (1J1B) varied from -5,120; -3,990; and -4,423 kcal/mol. According to the thermodynamic perspective, affinity energy greater than -4 kcal/mol is considered as the weak binding between protein and ligand caused by accidental van der Waals force, meaning no distinct interaction is already formed between them. This condition leads to an easily-dissociated complex in physiological conditions and difficulties to maintain proper interactions while competing with other proteins, highlighting that phenylacetonitrile does not directly interfere EGFR (4ZSE) function due to the affinity core is greated than -4 kcal/mol. On the other hand, interaction of phenylacetonitrile and ESR1 (7RS7) and GSK3B (1J1B) leads to binding affinity energy between -4 to -6 kcal/mol that is considered as weak interaction. This molecular docking simulation shows that phenylacetonitrile, as the most prominent lily-of-the-valley’s compounds may exert mild functions toward ESR1 (7RS7) and GSK3B (1J1B), but it does not necessarily possess great potential as a drug candidate in OSCC to the weak affinity scores.
According to this project, lily-of-the-valley has potential to interfere OSCC-related genes through mild molecular interactions toward particular genes, but since the overlapping genes reach only 0.8%, this indicates that lily-of-the-valley does not offer broad coverage toward the complex molecular routes of OSCC. Thus, different approaches are advisable to screen better OSCC drug candidates to maximize the inhibition of multiple pathways. 

References:

Eberhardt, J. et al. (2021) 'AutoDock Vina 1.2.0: new docking methods, expanded force field, and Python bindings,' Journal of Chemical Information and Modeling, 61(8), pp. 3891–3898. https://doi.org/10.1021/acs.jcim.1c00203. 

Gautam, D.Z.N.W., Krushna Rathod, Akansha Ramteke Bhushan Gandhare, Sadhana (2025) 'Pharmacological Insights into Convallaria Majalis (Lily of The Valley): From Traditional Uses to Scientific Validation,' Zenodo (CERN European Organization for Nuclear Research) [Preprint]. https://doi.org/10.5281/zenodo.15397225. 

Matsuo, Y. et al. (2017) 'Steroidal Glycosides from Convallaria majalis Whole Plants and Their Cytotoxic Activity,' International Journal of Molecular Sciences, 18(11), p. 2358. https://doi.org/10.3390/ijms18112358. 

Pahutyan, N. et al. (2025) 'Convallaria majalis (Lily of the Valley): A review of its cardiac glycosides, medicinal applications, and safety profile,' Bioactive Compounds in Health and Disease - Online ISSN 2574-0334 Print ISSN 2769-2426, 8(9), pp. 350–364. https://doi.org/10.31989/bchd.v8i9.1737. 

Pastorekova, S. and Gillies, R.J. (2019) 'The role of carbonic anhydrase IX in cancer development: links to hypoxia, acidosis, and beyond,' Cancer and Metastasis Reviews, 38(1–2), pp. 65–77. https://doi.org/10.1007/s10555-019-09799-0.

