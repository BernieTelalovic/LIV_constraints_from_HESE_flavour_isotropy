# LIV constraints from HESE flavour isotropy
This repository holds the .csv file containing constraints on LIV operators from the Standard Model Extension, dimensions 2,..., 8, for 68%, 95% and 99% confidence levels.

The columns of the resulting tables are:
 - 'd' [int]: the dimension of the operator. Takes values 2, ... , 8.
 - 'ell' [int]: the ell value of the spherical harmonic. Takes values 0, ..., d - 1 (for d = 2, only takes values 1),
 - 'm' [int]: the m value of the spherical harmonic. Takes values 0, ... , ell.,
 - 'alpha' [str]: the neutrino flavour specifying the row entry in the Hamiltonian. Takes values 'e', 'mu,, or 'tau',
 - 'beta' [str]: the neutrino flavour specifying the column entry in the Hamiltonian. Takes values 'e', 'mu,, or 'tau',
 - 'flavors_at_source' [str or tuple]: the assumed flavor ratio at the sources. Takes values 'agnostic', (1/3,2/3,0), (1,0,0) or (0,1,0),
 - 'Norm' [float]: the column containing the constraint of the norm of the LIV parameter specified with the parameters above,
 - 'Re' [float]: the column containing the constraint of the absolute value of the real component of the LIV parameter specified with the parameters above,
 - 'Im' [float]: the column containing the constraint of the absolute value of the imaginary component of the LIV parameter specified with the parameters above,
 - 'confidence_level' [int]: the confidence level at which the constrint is set. Takes values 68, 95 or 99.
