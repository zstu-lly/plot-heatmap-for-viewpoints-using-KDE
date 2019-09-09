# plot-heatmap-for-viewpoints-using-KDE
Plot heatmap for viewpoints using KDE(kernel density estimation), so that we can know the distribution of poses.

## About
To visualize viewpoints distribution in 6D pose dataset, I first convert rotation matrix to viewpoint in polar coordinate system.Let ρ be the distance of the optical center to the origin, θ and φ be the longitude and latitude, respectively.I use kernel density estimation (KDE) to estimate the non-parametric distributions of ρ,θ,φ for each category respectively from the LINEMOD Occluded dataset.
