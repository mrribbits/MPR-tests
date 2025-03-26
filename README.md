# MPR-tests

You'll find 3 text files that correspond to subcortical and cortical (lh/rh) Freesurfer 8 table outputs.

From one subject/ 3 different MPRAGE acquisitions:

1- MPR - standard MPRAGE: 1mm iso, GRAPPA=2	TR=2300, TE=2.96, TI=900, FA=9

2- WAVE CAIPI MPR - using MGH C2P: 1mm iso, R3x3	TR=2500, TE=3.48, TI=1100, FA=7

3- CS MPR - using Siemens WIP: 1mm iso, acc4x	TR=2300, TE=3.15, TI=900, FA=9


The Jupyter notebook will load one of the files and compare each accelerated acquisition to the standard one.
Just comment/uncomment the file you want to load.

