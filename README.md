# DLSC-CorMarices
This repo contains the trained correlation matrices for the bit-flipping metric computation of the DLSC decoder.<br />
The matrix is stored in both .txt and .npy formats.<br />
In Python, the following code reads the correlation matrix from a .npy file:<br />
<br />
""""""""""<br />
import numpy<br />
corMat = numpy.load(cormat_Nn_Kk_Cc.npy)<br />
""""""""""<br />
