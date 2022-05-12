n=int(input('inter n = '))
x=2*n 
k=0
for i in range(1,x):
    for j in range(1,x):
         
         if j<=k or j>=x-k :
             print(' ', end='')
         elif(i%2==0 and j%2==0) or (i%2!=0 and j%2!=0 )  :
              print('$', end='')
         else :
              print(' ', end='')
              
    print('')
              
    if i<n :
        k+=1
    else:
         k-=1
