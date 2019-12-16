# Interpolation
Python routines for point location within a partition and Vandermonde interpolation

This repository contains two Python scripts.  partition.py contains both a direct and recursive function to locate a given point within a partition of a segment of the real line and could be used when an interpolant is broken up into segments.  With a line segment divided into n partitions, the direct function takes O(n) iterations to locate where the point lies in the partition whereas the recursive function takes O(log2 n) iterations.  vandermonde.py contains a function to perform Vandermonde interpolation and tests this routine on a sample dataset.  vandermonde.pdf displays a plot of this test.
