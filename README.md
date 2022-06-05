def factorial_recursive(n):
    if n ==1:
        return 1
    else:
        return n * factorial_recursive(n-1)

print('enter a number please')
n=int(input())
print('The factorial of ',n , 'is', factorial_recursive(n))
