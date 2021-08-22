# dumb

op = input("Which operation do you wish to do? [add,minus,mult,div]")
first = int(input("what is the first number of this operation? "))
second = int(input("what is the second number of this operation? "))
if op == "add":
    re = (first + second)
    print(re)
elif op == "minus":
    re = (first - second)
    print(re)
elif op == "multi":
    re = (first * second)
    print(re)
elif op  == "div":
    re = (first / second)
    print(re)

print("Result of it is" + " " + str(re))
