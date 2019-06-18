# TMD_AsymmetricCoupling
This is to design TMD asymmetric coupling system for vibration control of twin buildings

The codes are to perform the multi-objective optimization of TMD asymmetric coupling system for vibration control of twin buildings. The codes are based on the paper as follows: Seung-Yong Ok, "TMD asymmetric coupling system for vibration control of adjacent twin buildings", 2019.

All programs can be performed based on the MATLAB progam by incorporating MATLAB Optimization Toolbox and Parallel Computing Toolbox. The codes should be unzipped by the folder names such as ACS1, ACS2, ACS3 and ICS.

In ICS folder, "Run_STMD_DSG.m" is a main program to design single TMD by using Den Hartog design formula.

In ACS1, ACS2 and ACS3 folders, "RunMain_M3.m", "RunMain_M4.m" and "RunMain_M5.m" are the main code to perform the multi-objective optimization.
Each design program produces the corresponding design results, named as "RunMain_M3_DsgResult.mat", "RunMain_M4_DsgResult.mat" and "RunMain_M5_DsgResult.mat".
Then, "RunMain_M3_Post.m", "RunMain_M4_Post.m" and "RunMain_M5_Post.m" are the post-processing programs to investigate the comparative performances of the three systems such as ACS1, ACS2 and ACS3. These post-process programs produce the post-process results, named as "RunMain_M3_PostResult.mat", "RunMain_M4_PostResult.mat" and "RunMain_M5_PostResult.mat".

The remaining files are the sub-functions for the main design and post-process.

One could modify the files to solve other similar problems of interest.
Acknowledgement: This study was supported by Basic Science Research Program through the National Research Foundation of Korea (NRF) funded by the Ministry of Education (2017R1D1A1B04031418).

