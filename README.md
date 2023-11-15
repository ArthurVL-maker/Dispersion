## dispersion.py - A Python algorithm for phase angle and amplitude correction of pressure bar signals

#### DESCRIPTION:

#### FILES INCLUDED:
- *dispersion.py*: A Python function, with the documentation on the use of the function included in the file as comments. It requires *dispersion_factors.py* to run.
- *dispersion_factors.py*: A Python function, with the documentation on the use of the function included in the file as comments. It requires the folder dispersion_factors.
- 'dispersion_factors' folder: A folder containing pre-calculated values of normalised frequency, normalised velocity and factors m1 and m2 for a material with a Poisson's ratio of 0.29 (i.e. stainless steel). This was calculated using the algorithm *phase_velocity.py* (Van Lerberghe, A., Barr, A. D. (2023)), available on GitHub and ORDA, see links below.

#### REFERENCES:
- Tyas, A., Pope, D.J., (2005). Full correction of first-mode Pochhammer–Chree dispersion effects in experimental pressure bar signals. Measurement science and technology, 16(3), p.642.

#### MATLAB SOFTWARE:
- Barr, A. D. (2016) *dispersion.m* - A Matlab script for phase angle and amplitude correction of pressure bar signals. University of Sheffield.\
Software ORDA link: [https://doi.org/10.15131/shef.data.3996876.v1]

#### PYTHON SOFTWARE:
- Van Lerberghe, A., Barr, A. D. (2023) *phase_velocity.py* - A Python algorithm for calculating frequency-dependent phase velocity and radial variation of elastic waves in cylindrical bars. University of Sheffield.\
Software ORDA link: [https://doi.org/10.15131/shef.data.22010999]\
Software GitHub link: [https://github.com/ArthurVL-maker/Phase_velocity.git]

#### AUTHORS:
Arthur Van Lerberghe <avanlerberghe1@sheffield.ac.uk> & Andrew D. Barr <a.barr@sheffield.ac.uk>.
