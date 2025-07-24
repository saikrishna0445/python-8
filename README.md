# python-8
tree recursion
#tree recursions
#fib on tree recursion
def fib(n):
    if n<=1:
        return n
    return fib(n-1)+fib(n-2)
terms=int (input("enter the no of terms:"))
print(("fibonacci series......"))
for i in range(terms):
    print(fib(i),end=' ')
