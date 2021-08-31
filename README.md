# Deep_genomic_divergence_and_phenotypic_admixture_of_the_treefrog_Dendropsophus_elegans


Phylogeography and Population genetics is South America

Scripts and input files for the analyses used in the manuscript submitted at the Frontiers in Ecology and Evolution:

Pirani, R.M., Tonini, J.F.R., Thomaz, A.T., Napoli, M.F., Encarnação, L., Knowles, L.L., Werneck, F.P.
Deep genomic divergence and phenotypic admixture of the treefrog Dendropsophus elegans (Hylidae: Amphibia) coincide with riverine boundaries at the Brazilian Atlantic Forest


Input files for the analyses presented in the manuscript.

1. Individuals reconstruction and relationship

  . D.elegans.nex: SVDQuartets Nexus individuals input file

2. Individuals reconstruction and relationship
  
  . RAxML_bipartitions.Delegans_tree: RaxML individuals file

3. Population genetic structure
  
  . North_14ind_5001snp.ustr: STRUCTURE input file within the North population
  
  . South_11ind_5001snp.ustr: STRUCTURE input file within the South population
  
  . Total_29ind_5001snp.ustr: STRUCTURE input file total species

4. Estimation of geographic barriers and gene flow
  
  . params-chain.ini: contains the parameters for each run
  
  . Deleg_transpose.coord: contains the samples localities
  
  . Deleg_transpose.diffs: contains the observed genetic dissimilarities
  
  . Deleg_transpose.outer: contains the estimated polygon around the species distribution

5. Demographic migration model for Dendropsophus elegans populations
  
  . doce_M_MSFS.obs: site frequency spectrum (SFS) for the minor allele for each population sample for the Doce River
  
  . doce_M.est: prior and rules for the migration model for the Doce River
  
  . doce_M.tpl: estimated parameters for the Doce River
  
  . guacu_M_MSFS.obs: site frequency spectrum (SFS) for the minor allele for each population sample for the Paraguaçu River
  
  . guacu_M.est: prior and rules for the migration model for the Paraguaçu River
  
  . guacu_M.tpl: estimated parameters for the Paraguaçu River
  
  . para_M_MSFS.obs: site frequency spectrum (SFS) for the minor allele for each population sample for the Paraíba do Sul River
  
  . para_M.est: prior and rules for the migration model for the Paraíba do Sul River
  
  . para_M.tpl: estimated parameters for the Paraíba do Sul River
  
  . ribeira_M_MSFS.obs: site frequency spectrum (SFS) for the minor allele for each population sample for the Ribeira do Iguape River
  
  . ribeira_M.est: prior and rules for the migration model for the Ribeira do Iguape River
  
  . ribeira_M.tpl: estimated parameters for the Ribeira do Iguape River


6. Species range expansion after the Last Glacial Maximum (LGM)
  
  . subdata2_North.nex: input files used to calculate the North population expansion implemented by X-Origin R script for Dendropsophus elegans species. 
  
  . subdata2_South.nex: input files used to calculate the South population expansion implemented by X-Origin R script for Dendropsophus elegans species. 
