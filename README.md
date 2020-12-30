# assignments (assignment 2 Numpy)
x = np.array([[0, 1, 2, 3, 4], [5, 6, 7, 8, 9]])
x
np.shape(x)
array1=np.array([[0, 1, 2, 3, 4], [5, 6, 7, 8, 9]])
array1
arr2 = np.array([[1, 1, 1, 1, 1], [1, 1, 1, 1, 1]])
arr2
np.vstack((array1,arr2))
np.hstack((arr,arr2))
array1.flatten()
b=np.reshape(a,(5,3))
b
c=np.random.rand(5*5)
c
c*c
b=np.random.rand(5*6)
b
np.mean(b)
np.std(b)
np.median(b)
b.T
diag = np.diagonal(n) 
diag
sum(diag)
np.linalg.det(n)
a=np.arange(10)
a
np.percentile(a,5)
np.percentile(a,95)
np.random.randint(0,3,(3,10))
