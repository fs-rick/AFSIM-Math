# AFSIM-Math
Some math routines written in AFSIM script

Right now, there is only code included to have a working normal CDF function to access from any AFSIM script.  The code itself is also written in AFSIM script.

# Test

Load the `test-normal-CDF.txt` startup file in the AFSIM IDE.  When you run it, it will output (to mission's standard output) a table of normal CDF values next to values obtained from R's `pnorm(x, 0 , 1)`.  They should match up.

# Usage

To use this code in your AFSIM scenario, just include `math/normal-CDF.txt`, and use the `pnorm()` function in your calling code.

# Appendix

The normal CDF code was ported from GSL (GNU Scientific Library).  Find a cached copy of the C code we ported in the `gsl-code` subdirectory.
