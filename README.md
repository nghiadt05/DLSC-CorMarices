# DLSC-CorMarices
This repo contains the trained correlation matrices for the bit-flipping metric computation of the DLSC decoder.
The matrix for a polar code is stored in both .txt and .npy formats.
In Python, the following code reads the correlation matrix from a .npy file:

""""""""""<br />
import numpy<br />
corMat = numpy.load(cormat_Nn_Kk_Cc.npy)<br />
""""""""""<br />
