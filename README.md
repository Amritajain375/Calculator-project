# Calculator-project
print("Simple Calculator")
a = int(input("enter your first number:"))
b = int(input("enter your second number:"))
operation = input("choose operation (+,-,*,/):")
if operation == '+':
    choice = int(input("enter choise (1-4):"))
    if choice == 1:
        print("result:", a + b)
    elif choice == 2:
        print("result:", a - b)
    elif choice == 3:
        print("result:",a * b)
    elif choice == 4:
        print("result:",a/b)
    if b != 0:
        print("result:",a/b)
    else:
        print("error: division by zero")
    print("invalid choice")
