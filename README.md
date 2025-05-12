# Hypervolumes
Code for using Ben Blonders Hypervolumes package.

When using the Guassian approach there are several paramteters that can be adjusted to imrpove performance. These are: Bandwidth, quantile requested, and sd.count. 
Bandwidth affects the shape of the kernel used.
Quantile requested refers to the bounry of the KDE.
sd.count refers to the number of standard deviations at which the hypervolume edge will be evaluated.

For more details on these here is the CRAN manual https://cran.r-project.org/web/packages/hypervolume/hypervolume.pdf.
