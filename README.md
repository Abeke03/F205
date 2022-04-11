# F205
A = [[1,2,1],
    [2,1,1],
    [3,2,1]]

B = [[1,2,1,2],
    [2,1,1,2],
    [3,2,1,2]]

result = [[0,0,0,0],
         [0,0,0,0],
         [0,0,0,0]]

for i in range (len(A)):
    for j in range (len(B[0])):
        for r in range (len(B)):
            result[i][j] += A[i][r] * B[r][j]
print(result)
                 
                 
