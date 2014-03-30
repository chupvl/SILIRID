# Vladimir Chupakhin
# chupvl@gmail.com
# University of Strasbourg, Strasbourg, France

SILIRID
=======
datasets for the paper: Simple Ligand-Receptor Interaction Descriptor (SILIRID) for alignment-free binding sites comparison by Vladimir Chupakhin, Gilles Marcou, Helena Gaspar, Alexandre Varnek


every SILIRID entry
1. is vector of 168 counts divided by comma.
2. is composed of 21 parts, where 20 are standard aminoacids and the last part is a metal (Na,Ca,Mg,etc).
2. have following order of amino acids: ILE, VAL, LEU, PHE, CYS, MET, ALA, TRP, ARG, LYS, TYR, HIS, GLU, ASP, GLN, ASN, THR, SER, PRO, GLY (plus Metal)
3. have following order of interaction counts (as a results of the sum of the bits) for amino acid: hydrophobic, aromatic face to face, aromatic edge to face, H-bond donated by the protein, H-bond donated by the ligand, ionic bond with protein cation and protein anion, and interaction with metal ion or other types of interactions.
