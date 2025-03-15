"""the code to print out specified number of line of  Fibonacci series"""

n=int(input("enter the number of terms you want to know about:"))
#the code prompt the user to enter the number of series he/she wants to print out

def series(n):#definition of a function of the name series

    a,b=0,1# variable declaration
    for series in range(n):# for loop for displaying user inputs
     print(a,end=" ")#this line will print out output on one line without skipping to the next line \n
     a,b=b,a+b
series(n)
# this code will print out the n terms which user had requested
my_name=input("enter the name of your school:")
print(my_name)
