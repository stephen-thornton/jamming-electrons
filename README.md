# jamming-electrons
Mathematica notebooks used to generate the figures in "Jamming and Unusual Charge Density Fluctuations of Strange Metals"

SpherePacking generates the sphere configurations used in Fig. 1(a). These are cropped in Inkscape and then saved as the vector image Fig1aInked.pdf.

PlasmonPictures does most of the figure generation for Fig. 1. It requires Fig1aInked.pdf to import, as well as plasmon.png and phonon.png. PlasmonPictures itself
generates plasmon.png and phonon.png, but they need to be saved manually as .png files, and then they are reimported to make the image size for the vector graphic
Figure 1 not too large. PlasmonPictures also generates Fig. 3 of the supplemental material.

AveragingChi creates Fig. 2.

AveragingChiRegionFinal creates Fig. 2 of the supplemental material.
