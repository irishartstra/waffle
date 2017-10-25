# waffle

The Matlab script JGR.m reads in the synthetic earthquake recordings, their direct P- and S-waves, and wavelet information from mat-file: V.mat. Next, elastodynamic full-field MDD (equation ) is applied to produce the two results in the manuscript (Figures 3e and 3k)

For generating synthetic earthquake recordings using fdelmodc: Install the finite-difference code, fdelmodc, developed by Jan Thorbecke. Source codes can be obtained directly from  https://github.com/JanThorbecke/OpenSource. More information and a fdelmodc-manual can be found on: https://janth.home.xs4all.nl/Software/Software.html. Elastodynamic double-couple responses can be generated with fdelmodc by using the shear-stress source Txz, which is selected with input parameter: source_type=2. In order to obtain responses to rotated double-couples, we additionally modelled responses of Txx and Tzz sources (source_type 4 and 3, respectively). 

