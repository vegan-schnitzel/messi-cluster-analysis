# MESSI Cluster Analysis

MESSIs are relatively small self-powered weather stations which continuously monitor multiple environmental parameters. The instruments are set up in allotments around Berlin (Germany) as part of the citizen science project [OpenUCO](https://www.geo.fu-berlin.de/met/wexicom/OpenUCO).

![messi locations](figs/locations.png)

In this university project, temperature data of August 2022 measured by MESSIs every 10min is used.

![temperature august](figs/tmp-verlauf.png)

[kmeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) is an unsupervised learning algorithm which separates samples into groups (*clusters*). Trying different sets of features and changing the total number of clusters, this analysis aims to find daily clusters that are reasonably consistent in time (i.e., in August).

The most up-to-date, somewhat automated, analysis is notebook #5 (`code/5-scaled-features-perday.ipynb`) and should exclusively be considered if details about the coding part are of concern.

![clustering](figs/clusters_scaled_perday/default-features/clusters.gif)

Further results are shown in the final presentation slides (`präsi-messi-clustering.pdf`).
