# fibonacci-series
#to find the fibonacci series using python code
def fibo(n):
    a = 0
    b = 1
    if n ==  1:
        print(a)
    else:
        print(a)
        print(b)
        for i in range(2,n):
            c = a + b
            a = b
            b = c
            print(c)

            
fibo(13)
0
1
1
2
3
5
8
13
21
34
55
89
144

     
   

