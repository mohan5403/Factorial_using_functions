# Factorial_using_functions
def fact(n) :
    if n == 1 :
        print(n,end=' = ')
        return 1
    else :
        print(n,end='*')
        return n*fact(n-1)
s1 = int(input('Enter value'))
n1 = fact(s1)
print(n1)
