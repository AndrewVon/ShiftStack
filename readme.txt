This is a README file for the project ShiftStack.
Created by Feng Haoran @ 20170921

ShiftStack is a small tool written in Python, 
based on "sep" "astronomy-net" and "astropy" project.

With ShiftStack we can stack FITS images taken by telescopes,
and stack them with small position shifts depended on time.
So the signal from faint moving objects can be collected in
one single pixel, making it easier to detect.

This project is just starting up.


# Install the python packages we need
numpy, astropy, sep can be installed with pip, and of course,
you need to have a version of python first. Python3.5+ is
recommended.

Besides, if the FITS file's header is in SCAMP mode, not SIP,
we need to install astrometry-net and using its wcs-pv2sip.


[Work to do]
- Use a better way to delete bright stars from images, so only
the signal from faint objects won't be missed.

- Find a way to crop FITS image without damaging wcs data,
so that we can use DS9 to know the RA and DEC of suspects.

- Finish my paperwork and pass it to my partner.

