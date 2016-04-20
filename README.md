# SEDs
		This repository contains the SEDs for Population III stars and 
	Pop III galaxies used in our paper (Mas-Ribas et al. 2016). See the 
	article for detailed descriptions of the parameters used, calculation 
	procedures and references. 

		The SEDs are computed for zero-metallicity stars (H_He only) in 
	the ZAMS phase. We use the stellar parameters from Schaerer 2002 
	(2002A&A...382...28S) and Marigo 2001 ( 2001A&A...371..152M) as 
	reported in Kubát 2012 (2012ApJS..203...20K). 

	Every file contains two columns:
		First column - frequency     [Hz]
									The SEDs have been computed into a common frequency 
									array of 19 000 points linearly spaced from 5e12 to 
									5e16 Hz. The values have been computed using linear 
									interpolation.
		Second column - flux         H_\nu [erg s^{-1} cm^{-2} Hz^{-1} sr^{-1}( {M_\odot}^{-1}
									for the case of galaxy SEDs)].
									Note that this is the Eddington flux, so one needs to 
									multiply by 4\pi to obtain the flux F_\nu.

## Stellar SEDs
The names of the files denote the stellar mass.

## Galaxy SEDs
The names of the files denote the parameters of the IMFs; e.g, IMF_m9M50a2 means a population with lower stellar mass
limit of 9 solar masses, upper limit 50 solar masses and Salpeter slope, -2.35. Note that the top-heavy IMF has a 
slope of "0" in linear space, not logarithmic.

If you found the SEDs useful for your work, please cite us.

If you find any mistake in the SEDs, please let us know and we will try to fix it as soon as possible.




