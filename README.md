# CHEM5630
'''
AHNA is an algorithm set to create homodimer structures from monomer data 
Automated Homomer Structure by NMR (AHNA) is a computational approach that can be used to determine the three-dimensional structure of homodimers using NMR spectroscopy data. The technique is based on the fact that homodimers are composed of two identical subunits, which have the same NMR spectra, but may have different intermolecular interactions.

AHNA uses a combination of NMR-derived data, including NOE (nuclear Overhauser effect), RDC (residual dipolar coupling), HBDA (hydrogen bond distance and angle), and H-bond
(hydrogen bond strength) data to compute the lowest energy homomer conformation. This approach enables the determination of homodimer structures, even for larger and more dynamic proteins that may be challenging to study using traditional NMR methods.

AHNA runs with XPLOR NIH, a Python package originally derived from the X-PLOR program developed by A. Brünger as a fork
of the CHARMM molecular dynamics program around 1984.

XPLOR can be downloaded at https://bit.niddk.nih.gov/xplor-nih/ or be accessed through NMRbox.org
(XPLOR installion tutorial: https://nmr.cit.nih.gov/xplor-nih/doc/current/python/tut.pdf)
Attached is all necessary input files - for Spanish Flu (PDB 2m74) for the code to duplicate and generate the homodimer structure. Final output file would be ahna_dimer_*.pdb. The strucutre can be analyzed using PyMol or VMD. 
'''
