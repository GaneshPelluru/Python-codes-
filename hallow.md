#This is the code for printing the hallow right angle triangle for numerical values in python........
'''
approach 1
n = int(input())
for i in range(1, n+1):
    for j in range(1, n+1):
        if (i == j) or (j == 1) or (i == n):
            print("*", end=" ")
        else:
            print(" ", end=" ")
    print()
'''
#approach2
n = int(input())
for i in range(n):
  for j in range(n):
    if i<=j and i == j or j == 0 or i==(n-1):
      print(f"{i}{j}", end=" ")
    else:
      print("  ", end=" ")
  print()


  #output looks like:

  ![image](https://github.com/GaneshPelluru/Python-codes-/assets/128490912/9ad4695c-1c7e-4252-91e4-ca620741a6d4)

