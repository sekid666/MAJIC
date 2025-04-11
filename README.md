# MAJIC

# this script computes MAJIC (Mean Across Jaccard Index Checkerboards) to quantify the influence of focal species on community composition. 

# It was specifically written for a longitudinal data-set of infant gut microbiota and their respective mothers. Hence, this script repeats the same analysis for 4 different "time-points": 2 months post-delivery (B-02), 6 months post-delivery (B-06), 11 months post-delivery (B-11), and maternal samples (M)

# users should download respective phyloseq-objects before running this script. For each, pre-filtering was applied (abundance and prevalence), as described in the manuscript. However, any user can apply this script to their own phyloseq objects and their own purposes.

# This script assumes the user has a working R installation with relevant libraries installed
