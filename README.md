# F205
A = [[5,3,1],
    [2,1,7],
    [3,5,1]]

B = [[4,2,1,2],
    [2,15,1,2],
    [3,2,11,27]]

result = [[0,0,0,0],
         [0,0,0,0],
         [0,0,0,0]]

for i in range (len(A)):
    for j in range (len(B[0])):
        for r in range (len(B)):
            result[i][j] += A[i][r] * B[r][j]
print(result).
                 
                 
