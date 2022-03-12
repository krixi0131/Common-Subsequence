# Common-Subsequence
```python
x=int(input())
for i in range(x):
    n,m=map(int,input().split())
    a=list(map(int,input().split()))
    b=list(map(int,input().split()))
    check=0
    for ii in range(n):
        for iii in range(m):
            if a[ii]==b[iii]:
                print("YES")
                print(1,a[ii])
                check=1
                break
        if check==1:
            break
    if check==0:
        print("NO")             
    
```
