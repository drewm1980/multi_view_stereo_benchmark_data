# The Dataset for the Robovision Multi View Stereo Benchmark

See README.md in the git@github.com:drewm1980/multi_view_stereo_benchmark.git for more info.

Note, this is intended to be downloaded as a git submodule of the above repo.

`reference_reconstructions` contains reconstructions produced by taking a relatively high quality pmvs reconstruction, and deleting any obvious outliers in meshlab.

undistorted_images contains the source images from the camera array. They are already corrected for radial distortion, and camera intrinsics and extrinsics (internal and external parameters) are provided. 

Camera calibration routines from HALCON 12 were used, so that's the currently the file format.  However, python scripts for parsing this format are providede in the main benchmark repository.
