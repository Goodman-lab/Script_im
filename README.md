# Script_im
Scripts for computational investigations of large and flexible chemical systems based on the conformation labelling system, ONIOM calculations in Python 3

Filter_diversity_incl_label_generation_and_selection.ipynb
-	The label generation and selection process have been integrated into the same script 
-	Take a xyz file + dihedral angle of interests and return the selected conformers as a list (numerical index from the conformation searching output file) 
-	Examples have been included 

conformation_label_generation.ipynb
-	Take a xyz file + dihedral angle of interests and return the conformation labels of the conformers in the file as a data frame 
-	Two Examples have been included 

Selection_remove_repetitive_structures.ipynb
-	Take a dataframe that contains the conformation label and ΔG‡ value of the conformers and return a list of selected conformers (as numerical index – inherit from the conformation searching output file) 
-	An Example has been included 

gjf_generation.ipynb
-	The output from ‘Filter_diversity_incl_label_generation_and_selection’ can be directly used as the input for generating the gjf 
-	The naming of the gjf file is controlled by ‘by_num’: 
by_num = ‘no’ -- filename given in the xyz file + a user-specified suffix (input as a string)
by_num = ‘yes’ or other string -- filename of the xyz file + a number (the index of the conformer in the xyz file) 
-	Two examples have been included
