
[![Build Status](https://travis-ci.org/scienceopen/pymap3d.svg)](https://travis-ci.org/scienceopen/pymap3d)
[![Coverage Status](https://coveralls.io/repos/scienceopen/pymap3d/badge.svg)](https://coveralls.io/r/scienceopen/pymap3d)
==============

Python coordinate conversions, following convention of several popular Matlab routines. Atmospheric effects neglected in all functions not invoking AstroPy.

Prereq:
```
git clone --recursive https://github.com/scienceopen/pymap3d
pip install -r requirements.txt
```

Consider using [python-geopy](https://pypi.python.org/pypi/geopy) as well.
For example, if you're seeking [Vicenty distance](http://geopy.readthedocs.org/en/latest/#module-geopy.distance).

Popular mapping toolbox functions ported to Python include:
```
aer2ecef
aer2enu
aer2geodetic
aer2ned
ecef2aer
ecef2enu
ecef2enuv
ecef2geodetic
ecef2ned
ecef2nedv
ecef2eci
eci2ecef
enu2aer
enu2ecef
enu2ecefv
enu2geodetic
geodetic2aer
geodetic2ecef
geodetic2enu
geodetic2ned
ned2aer
ned2ecef
ned2ecefv
ned2geodetic 
vreckon
```
for converting right ascension and declination to azimuth and elevation, [please see the function radec2azel](https://github.com/scienceopen/astrometry/)

or simply use the functionality of [AstroPy 1.0+ to do radec->azel conversion](http://astropy.readthedocs.org/en/v1.0/whatsnew/1.0.html#support-for-alt-az-coordinates)
