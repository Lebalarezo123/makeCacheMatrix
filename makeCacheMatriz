# makeCacheMatrix
## Put comments here that give an overall description of what your
>     ## functions do
>     
>     ## Write a short comment describing this function
>     #The first function will create a matrix that can cash its inverse
>     
>     makeCacheMatrix <- function(x = matrix()) {
+         I <- NULL
+         #set the matrix
+         set <- function(y) {
+             x <<- y
+             I <<- NULL
+         }
+         # get the matrix
+         get <- function() x
+         
+         # inverse of the matrix
+         setsolve <- function (solve) I <<- solve
+         
+         # return the matrix
+         getsolve <- function () m 
+         
+         list (set=set, get=get, 
+               setsolve=setsolve,
+               getsolve=getsolve)
+     }
>     
>     
>     ## Write a short comment describing this function
>     # the second function computes the inverse of the matrix created above
>     
>     cacheSolve <- function(x, ...) {
+         ## Return a matrix that is the inverse of 'x'
+         I <- x$get()
+         if(is.null(I)) {
+             message("getting inverse matrix")
+         }
+         data <- x$get()
+         
+         # calculation of the inverse of the matrix using multiplication
+         I <- solve(data,...)
+         
+         # set the inverse to object
+         x$setsolve()
+         
+         # return the matrix
+         I
+     }
> 
