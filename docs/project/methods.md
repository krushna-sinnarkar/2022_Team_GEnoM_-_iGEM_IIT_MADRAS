# Methods

<hr style="height:3px;border:none;color:#808080;background-color:#808080;" />

# **An overview of the computational methods used**

Various software including pSTAB, pyMOL and PropKa have been used to find and model the most stable mutant of cytosine deaminase at pH 5

**pStab web server:** The pStab webserver predicts the variation in stability of protein mutants under varying experimental conditions of ionic strength and temperature using the electrostatic  Debye-Hückel interaction energy of charged residues. A structure based statistical mechanical model is then employed to predict the thermal stability of the mutants. The server gives a stability-sorted list of the top 5000 mutants ordered based on their net electrostatic interaction energies and locations of mutational hotspots.

**propKa:** propKa web server provides an empirical method to predict the variation of pKa values of protein’s side chains based on the position of the group and chemical interactions with other groups in its vicinity. Using the tool, Intra-protein electrostatic interactions of the amino acid residues at the active site of the target enzyme was identified. Any mutation affecting amino acid residues interacting with the active site amino acid residues was avoided. 

**pyMOL:** pyMOL is a powerful molecular simulation software to visualize the three dimensional structure of proteins and other macromolecules. pyMOL was used to generate the PDB files of stable mutant enzymes identified from the pStab server. The PDB of the mutant molecule was uploaded to pSTAB and the electrostatic energy of the triple mutants were obtained to analyze their stability.

<hr style="height:3px;border:none;color:#808080;background-color:#808080;" />

# **An overview of the Experimental Design**

<h2 style="margin: 0 !important;">Bacterial Strains</h2>

<ul>
  <li><h3 style="margin: 0 !important;">The bacterial strain E. coli GIA39 (DE3) is used in the cloning process.</h3></li>
  <li><h3 style="margin: 0 !important;">The strain is a cytosine deaminase deficient strain which is used for genetic complementation assays to verify cytosine deaminase activity.</h3></li>
  <li><h3 style="margin: 0 !important;">The strain E. coli BL21(DE3) is used for protein overexpression.</h3></li>
  <li><h3 style="margin: 0 !important;">As for the Vector backbone that will be carrying the yCD gene, the plasmid pET15b is chosen.</h3></li>
  <li><h3 style="margin: 0 !important;">Restriction enzymes NdeI and BlpI are chosen within the T7 region, which is present in the plasmid.</h3></li>
  <li><h3 style="margin: 0 !important;">The plasmid will be digested by enzymes at sites NdeI and BlpI to insert the yCD gene.</h3></li>
</ul>

<h2 style="margin: 0 !important;">Primer Design</h2>

<ul>
  <li><h3 style="margin: 0 !important;">yCD gene sequence from Saccharomyces cerevisiae genome is imported to SnapGene software</h3></li>
  <li><h3 style="margin: 0 !important;">The ideal primers are expected to have a melting temperature (Tm) in the range of 55°C to 70°C with flanking sequences that do not support dimer formation.</h3></li>
  <li><h3 style="margin: 0 !important;">The forward and reverse primers are designed using tools in SnapGene. They have melting temperatures of 64°C and 65°C respectively with GC stability in the range of 40 - 50%. The primers have a size of 30-40 nucleotides with the common flanking sequence, TAAGCA, to ensure precise restriction digestion. </h3></li>
  <li><h3 style="margin: 0 !important;">The ligation of the yCD gene with the plasmid vector is ensured by including compatible restriction sites NdeI in the forward primer and BamHI in the reverse primer.</h3></li>
  <li><h3 style="margin: 0 !important;">The yCD gene is then PCR-amplified with the designed primers in SnapGene, followed by its ligation with the double-digested pET15b vector at the NdeI and BlpI restriction sites.</h3></li>
</ul>

Forward (31mer, Tm =59℃) : TAAGCACATATGATGGTGACAGGGGGAATGG 
Reverse (38mer, Tm=55℃) : TAAGCAGCTNAGCCTACTCACCAATATCTTCAAACCAA

<h2 style="margin: 0 !important;">Primer Design</h2>

<ul>
  <li><h3 style="margin: 0 !important;"></h3></li>
</ul>

[Back to top](#)
