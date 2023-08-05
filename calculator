def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    return x / y

def calculator():
    print("Calculator turned on")
    while True:
        print("Select operation:")
        print("1. Addition(+)")
        print("2. Subtraction(-)")
        print("3. Multiplication(*)")
        print("4. Division(/)")
        print("5. Exit")

        select = input("Enter your choice of operation (1-5): ")

        if select == '5':
            print("Calculator turned off.")
            break

        if select in ('1', '2', '3', '4'):
            num1 = float(input("Enter the first number: "))
            num2 = float(input("Enter the second number: "))

            if select == '1':
                print(num1,"+",num2,"=",add(num1, num2))
            elif select == '2':
                print(num1,"-",num2,"=",subtract(num1, num2))
            elif select == '3':
                print(num1,"*",num2,"=",multiply(num1, num2))
            elif select== '4':
                if num2!=0:
                    print(num1,"/",num2,"=",divide(num1, num2))
                else:
                    print("Cannot divide by zero.")
        else:
            print("Invalid input. Please try again.")

calculator()
