PALM algorithm:
Implementation of an algorithm for reconstructing all signals of the monitored object based only on measurable online signals. Adaptive signal estimation algorithm with additional tuning of dynamic properties through forced eigenvalue localization. The algorithm uses a specially designed latch mechanism. The solution concerns an original approach to signal processing methods and procedures describing the dynamic process of monitoring a polluted river.

Development environment:
- MatLab R2022a

System architecture:
- PALM.m - the main program that solves the problem of monitoring with forced dynamics;
- object.m - the function that models the signals in the three-section river river investigated;
- riccati.m - the function that calculates the value of filter gain;
- gauss.m - stochastic noise generator;
- createfigure.m - support function generating the graphics base for the presented results;
- compare_vari_inter.m - the assistant program that creates charts of indicators of the quality of the signals generated;
- wwA_fig.m - the function that creates a graph of the distribution of eigenvalues;
- DATA - folder containing selected data files with average results of MAE and RMSA values obtained with different conditions for compare_vari_inter.m program;
- SAVEDATA - folder for saving assistance data;

Contact:
- przemyslaw.hawro@pwste.edu.pl
