# ETRO's Bjontegaard Metric implementation for Excel.		
		
## Description:

Excel VBA code for calculating Bjontegaard Delta SNR and Rate, using arbitrary number of data points. The calculated results comply with VCEG-M33 when using 4 data points.

Provides two functions (all arguments take cell ranges):

	BDSNR(BR1, PSNR1, BR2, PSNR2)
	BDBR(BR1, PSNR1, BR2, PSNR2)

These functions are provided in two versions (both containing the exact same VBA code):

1. __bjontegaard_etro_standalone_example.xlsm__ is a stand-alone Excel sheet with the VBA routines internally in the file. It’s a macro-enabled Excel worksheet.

1. __bjontegaard_etro.xla__ is an Excel Add-In. By adding this on your system (via Excel Add-In preferences), the two functions become globally available in your Excel install.

##Author:

Tim Bruylants, ETRO, Vrije Universiteit Brussel
		
##References:

	[1] G. Bjontegaard, Calculation of average PSNR differences between RD-curves (VCEG-M33)
	[2] S. Pateux, J. Jung, An excel add-in for computing Bjontegaard metric and its evolution
		
_Copyright (C) 2013 Tim Bruylants, ETRO, Vrije Universiteit Brussel._
