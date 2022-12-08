# using-try-funtion-in-python
a=int(input("enter a number"))
b=int(input("enter a number"))
try:
    c=a/b
except:
    print("a number cannot divided by 0")
else:
    print(c)
finally:
    print("program excuted")
#output:-
enter a number 78
enter a number 0
a number cannot divided by 0
programm excuted
