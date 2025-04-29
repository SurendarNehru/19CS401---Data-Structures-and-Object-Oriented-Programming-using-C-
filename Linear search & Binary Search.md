# AIM:
To write a C++ program to implement Linear Search on a given set of integers and find the index of the searched element.


# ALGORTHIM:

1.Start<br>
2.Declare an array (to simulate a tuple) and input its size and elements.<br>
3.Input the element to search (key).<br>
4.Traverse the array using a loop:<br>
5.Compare each element with the key.<br>
6.If match found, print the index and stop.<br>
7.If loop ends and no match is found, print "Element not found".<br>
8.End<br>

# PROGRAM:

```
def search(tuple1,x):
    for value in tuple1:
        if(value==x):
            print("%d Found"%x)
            return 0
    print("%d Not Found"%x)
    
List=[]
n=int(input())
for i in range(n):
    List.append(int(input()))
tuple1=tuple(List)
x=int(input())
search(tuple1,x)
````

# OUTPUT:'

![image](https://github.com/user-attachments/assets/9d3572ae-7b93-4983-b118-1a3b282f362d)



# RESULT:

The C++ program for Linear Search was successfully executed.
