Pharmacophore and QSAR
---
This project showcases the workflow of pharmacophore modeling, molecular feature extraction, and QSAR (Quantitative Structure-Activity Relationship) modeling to predict the binding energy of ligands. The project covers molecular visualization, feature extraction, and binding energy prediction using machine learning models.

The project was done in jupyter notebook
---
Project Structure:
1. Prepare Ligand
2. Prepare Protein
3. Docking with AutoDock Vina*
   - make sure that autodock vina is installed and can be access via bash
4. Pharmacophore Modelling
5. QSAR
---
Requirements
- python 3.x
- libraries
  - rdkit
  - os
  - MDAnalysis
  - pdb2pqr
  - openbabel
  - autodock vina
  - py3Dmol
  - numpy
  - pandas
  - scikit-learn
---
Files:
Input file: 
  input file used in this project is '3ktr.pdb'.

output:
  some files will be generated throughout the project, all of the generated files will be used for other function such as docking or creating dataframe. Overall, the output will be shown in the output cell of the jupyter notebook. The generated files will be saved in 'docking' folder.

Code:
  The code used in this project is Pharmacophore_QSAR.ipynb
---
How to run:
  1. Run the Jupyter Notebook file step-by-step to process the data.
  2. Customize SMILES string or ligand features as needed.

*most of the library used could be installed through !pip except autodock vina. If the program could not compile because an error when calling !vina, make sure to have vina installed and added to system path.
