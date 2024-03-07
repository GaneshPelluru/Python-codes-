> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.
## program for the code 
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


  # output looks likes as:
  ![image](https://github.com/GaneshPelluru/Python-codes-/assets/128490912/10671672-9840-4b39-a1ae-f37d0357f83c)

