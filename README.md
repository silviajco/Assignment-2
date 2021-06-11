# Assignment-2
mat <- makeCacheMatrix()

## set the matrix value
mat$set(matrix(data = (1:10), nrow = 5, ncol = 2))

## Check that we stored it correctly
mat$get()
# [,1] [,2]
# [1,]    1    6
# [2,]    2    7
# [3,]    3    8
# [4,]    4    9
# [5,]    5   10
