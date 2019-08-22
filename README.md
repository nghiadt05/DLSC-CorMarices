# DLSC-CorMarices
This repo contains the trained correlation matrices for the bit-flipping metric computation of the DLSC decoder.<br />
A matrix is stored in both .txt and .npy formats.<br />
In Python, the following code reads the correlation matrix from a .npy file:<br />
##########<br />
import numpy<br />
corMat = numpy.load('cormat_Nn_Kk_Cc.npy')<br />
##########<br />
where n is the code length, k is the number of information bits, and c is the size of the CRC.<br />
The FER/BER curves of various decoders are also given for reference.
