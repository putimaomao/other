other
=====

###Other bash scripts

#####align_movie_frames

Script reads list.txt produced by prep_movie script and split it for parallel processing on CPU/GPU. Frames and average image will be converted to mrc format, aligned and summed by motioncorr program.

---
#####prep_montage

This script produces mount (both img and mrc) images from spotscan images (acquired on CM120) and also perform block convolution with low-pass filtering

---
#####prep_movie

The script looks for raw and tif files in current directory (including subdirectories) and produces a list.txt: frames/average tif

---
#####process_serialEM_montage

The script will split SerialEM mrc stacks (acquired on F20) into tiff files and produce a stack of power spectrums, thresholded and masked.

---
#####spotscan_clean_boxes

This script processes box files from CM120 spotscan (taken with 1024x1024px Gatan CCD camera) to remove particles on the border between montaged images and also the boxes outside micrograph.

---
