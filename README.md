# Applying the Kuwahara filter to an image

This code is about applying the Kouhara filter to an image.
The Kuwahara filter is a non-linear smoothing filter used in image processing for adaptive noise reduction. Most filters that are used for image smoothing are linear low-pass filters that effectively reduce noise but also blur out the edges. However, the Kuwahara filter is able to apply smoothing on the image while preserving the edges.

The process of filtering Kuwahara is basically the division of a pixel grid into four overlapping sub-grids, calculating an average and variance for each one. 
