# def calculate(num1, num2, num3, operation):
  if operation == 'add':
        return num1 + num2 + num3
  elif operation == 'subtract':
        return num1 - num2 - num3
  elif operation == 'multiply':
        return num1 * num2 * num3
  elif operation == 'divide':
        if num2 != 0 and num3 != 0:
            return num1 / num2 / num3
        else:
            return "Error: Division by zero"
  else:
        return "Error: Invalid operation"
    
num1= float(input("num1"))
num2= float(input("num2"))
num3= float(input("num3")) 
operation= input("choose operation: add, subtract, multiply, divide")
result = calculate(num1, num2, num3, operation)
print(f"The result of {operation} is: {result}")ython-w1-assignment
