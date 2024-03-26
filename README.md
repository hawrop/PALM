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
- SAVEDATA - folder for saving assistance data;

Data:
DATA folder containing test measurement data from the object and data generated from the object model (object.csv), as well as .txt files with selected average results of RMSE and MAE monitoring quality indicator values obtained under different conditions for the compare_vari_inter.m program;

Contact:
- przemyslaw.hawro@pwste.edu.pl
