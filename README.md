# Assignment Matrices -
 
## Contains the following three sets of matrices :
A. Supposed to --- Fixed : C.N = 1000 and Sparsity = 16%.      
                   Vary : sizes = 3000x3000, 1024x 1024, 128x128 - (3 matrices). 
   Instead took ---- For C.N instead of 1000, took the order 10^4 - 38093, , 10175, 9436.

B. Fixed : Size = 512x512 and Sparsity = 18%.  
   Vary : C.N = 100 (2944 instead), 10000 (9157), 1000000 (928109) - (3 matrices). 

C. Fixed : Size = 128x128 and C.N = 10000.     
   Vary : Sparsity = 16% (9789), 30% (9193), 45% (9439) -(3 matrices).
   
   
# Results -


A. 128 x 128 (16%) ran. B implies probable Memory Error for 1024x1024 and 3000x3000.

B. Memory Error for all.

C. Values turned out to be same for x_i's (mostly due to uniform QUBO landscape) - could run for 16%, Memory error for 45%.

Left to do : 30 % (9193)

CN: 9789 , D : 16% ---> L.F : 428.14

CN: 9436 , D : 16% ---> L.F : 696.01

# Conclusion -

Dense matrices not a cup of tea for QA.
