# Hypervolumes
Code for using Ben Blonders Hypervolumes package.

When using the Guassian approach there are several paramteters that can be adjusted to imrpove performance. These are: Bandwidth, quantile requested, and sd.count. 
Bandwidth affects the shape of the kernel used.
Quantile requested refers to the bounry of the KDE.
sd.count refers to the number of standard deviations at which the hypervolume edge will be evaluated.

For more details on these here is the CRAN manual https://cran.r-project.org/web/packages/hypervolume/hypervolume.pdf.

I should also point out that more empirical data points will produce a more relaible hypervolume - and too few points won't work at all (I think the minimum I could use was 7).
