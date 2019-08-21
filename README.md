# DLSC-CorMarices
This repo contains the trained correlation matrices for the bit-flipping metric computation of the DLSC decoder for 5G polar codes. The matrix for a polar code is stored in both .txt and .npy formats.
In Python, the following code reads the correlation matrix from a .npy file:
""""""""""
import numpy
corMat = numpy.load(cormat_Nn_Kk_Cc.npy)
""""""""""
