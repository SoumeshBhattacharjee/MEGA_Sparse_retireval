# MEGA_Sparse_retireval
This sparse matrix generator and retrieval program is used to generate a sparse matrix of 10,000,000 x 30000 fields where each of the 10,000,000 rows have their own  variation of numbers from the 30000 columns . it is used for mainly Cross country delivery data storage. Calculations done on a supercomputer , DO NOT TRY in your local computer, 

Scaled up version of small sparse matrix verison of the same author.


The sparsematrix is created in a CSR storage format and stored as sparse_matrix.npz The UI version is there to retrieve a a specific one product id and find the associated pincodes it can deliver .

I was unable to find datasets for the data of merchants and pincodes so sparse_matrix.py makes the datasets necessary. Computed in a supercomputer/ cloud based solutions.  IF doing in local system , try the small
or medium version of this.
sparsetest is a simple testing algorithm which also looks for the edgecases and all .

Happy coding . Also im a beginner so feel free to pull and commit .
