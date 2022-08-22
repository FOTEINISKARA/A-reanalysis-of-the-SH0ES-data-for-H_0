
			*** A reanalysis of the SH0ES data for Η0 ***  

---------------------------------- NUMERICAL ANALYSIS ----------------------------------------------------------

The Mathematica (version 11.0) files used for the numerical analysis and for construction of the figures are the following:

1. Baseline1_structure_of_system.nb (Baseline model in the absence  of the inverse distance ladder constraint)

2. Baseline2_ inverse_distance_ladder_constraint.nb (Baseline model in the presence of the inverse distance ladder constraint on M_B)

3. Figs_1_3_C1_C3.nb (Reanalysis of Individual Cepheid m_W slope data. Homogeneity of the Cepheid modeling parameter b_W)

4. Figs_2_4_5_C2.nb (Reanalysis of Individual Cepheid m_W slope data. Homogeneity of the Cepheid modeling parameter Z_W)

5. Fig_6.nb (Generalized Model Analysis- Search for a transition on M_B)

6. Fig_7.nb (Generalized Model Analysis- Search for a transition on b_W)

7. Fig_8.nb (Generalized Model Analysis- Search for a transition on M_W)

8. Figs_9_10_11 (Generalized Model Analysis- Search for a transition on Z_W - figures for the four transition models)

9. Figs_12_13 (Generalized Model Analysis- Search for a transition on M_B in the presence of the inverse distance ladder constraint on M_B)



--------------------------------- DATA----------------------------------------------------------

The data files used in our analysis are the following:

1. The Y=data vector, L=equation matrix (also includes some data), C=covariance matrix obtained  on 25/06/2022 from .fits files of the released 
dataset at Github repository: https://github.com/PantheonPlusSH0ES/DataRelease 

These .fits files are:

	ally_shoes_ceph_topantheonwt6.0_112221.fits=y, data vector
	alll_shoes_ceph_topantheonwt6.0_112221.fits=L, equation matrix
	allc_shoes_ceph_topantheonwt6.0_112221.fits=C, covariance matrix

2. The file dist.txt provides the distances of 42 galaxies. These distances obtained from: NASA/IPAC Extragalactic Database 
(https://ned.ipac.caltech.edu/).

3. The file distc.txt includes the distances that may be assigned to 3215 entries of the data-vector Y 
(2150 Cepheids in 37 SnIa hosts, 980 Cepheids in non SnIa hosts, 77 SnIa in Cepheid hosts and 8 constraints).

4. The file distall.txt includes the distances that may be assigned to 3292 entries of the data-vector Y 
(2150 Cepheids in 37 SnIa hosts, 980 Cepheids in non SnIa hosts, 77 SnIa in Cepheid hosts, 8 constraints and 277 SnIa in Hubble flow).

5. The files galblack.txt and galblacker.txt include the data that correspond to points shown in Fig. 10 of Riess 21 
(obtained using plot digitizer).

6. The file logp.txt includes the logarithm of period of the 3130 Cepheids 
(2150 Cepheids in 37 SnIa hosts, 980 Cepheids in non SnIa hosts).

7. The files galrank.txt and galrankmc.txt include properties of the Cepheid hosts considered in the analysis:
	1: Ranking in Table 3 in R21
	2: Ranking in Vector Y 
	3: Ranking in Figure C3 (Figure 10 of Riess 21)
	4: Galaxy name
	5: Distance obtained from: NASA/IPAC Extragalactic Database 
	6: Number of fitted Cepheids 
	7: Initial point in Vector Y
	8: Final point in Vector Y













