# MagLab
This repository contains:
## [Coordinate Files](https://github.com/Rtavakol/MagLab/tree/main/Coordinate%20Files)
Are Notebooks written in Python to generate coordinates associate with a magnetic coil. One can copy coordinates and paste in BiotSavart software.
## [.biot Files](https://github.com/Rtavakol/MagLab/tree/main/Biot%20Files)
.biot files are magnetic field simulation files created by BiotSavart Software. Link to [BiotSavart](http://www.ripplon.com/BiotSavart/)
## [Results Files](https://github.com/Rtavakol/MagLab/tree/main/Results%20Files)
Results of magnetic field simulation is plotted in notebooks written in Python. The software has its own graphical features to demonstrate the results. But one may want to explore it more. So, results have been exported as txt file and plotted in these notebooks.
## [Shimming Coil](https://github.com/Rtavakol/MagLab/tree/main/Shimming%20Coil)
Contains .biot, notebook, field data and field gradient data files. 
* .biot contains three 1st order and five 2nd order gradient coils. The coils are Bz ~ X, Y, Z, X^2 - Z^2, Y^2 - Z^2, XY, XZ and YZ coils. For more information about coils, have a look at [Anderson's paper](https://aip.scitation.org/doi/10.1063/1.1717338) on shimming coil. The paper is published in 1961! 60 years ago but still usefull. Another usefull paper on shimming can be found here: [McDowell's paper](https://www.sciencedirect.com/science/article/pii/S1090780718302337#f0010).
* Notebook contains python codes to visualize field and gradient profiles for 1st and 2nd order gradients. The data file associate with field and gradient files can be found at [Field](https://github.com/Rtavakol/MagLab/tree/main/Shimming%20Coil/Individual_Fields) and [Gradient](https://github.com/Rtavakol/MagLab/tree/main/Shimming%20Coil/Individual_Gradients)
* You can find dimension of coils at [Geometry](). 
* $$
\frac{n!}{k!(n-k)!} = {n \choose k}
$$
