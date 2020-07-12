# PAN_STARRS_interpolation
Author: Aniket Sanghi

Institution: The University of Texas at Austin

This is general purpose notebook to interpolate bolometric magnitudes using PAN-STARRS photometry in g, r, i, z bands 
as the input. The interpolation is made utilizing Table B1. from ***Deacon, N.R., Kraus, A.L., Mann, A.W., et al. 2016, MNRAS, 455, 4212***

Follow the USER comments for instructions on utilizing this notebook. Users will commonly have to modify only the action required cell. You will need to clone and download the entire repository so that the relevant text file (containing the grid) can be utilized for interpolation. If you get NaNs in your interpolation, it is likely that the input photometry is outside the range of the defined table used for the interpolation
