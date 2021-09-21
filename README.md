for i in range(1,11):
    for j in range(1,21):
        if j>=12-i and j<=10+i:
            print("*",end="")
        else:
            print(" ",end="")
    print()
