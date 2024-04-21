firstNumber = int(input("Enter number :"))
secondNumber = int(input("Enter number :"))
operation = input('''What mathematical operation do you want to perform? :
(Toplama : +, Çıkarma : -, Çarpma : *, Bölme : /)
''')

if operation == "+" :
    print("Sonuç :" + str(firstNumber + secondNumber))
elif operation == "-" :
    print("Sonuç :" + str(firstNumber - secondNumber))
elif operation == "*" :
    print("Sonuç :" + str(firstNumber * secondNumber))
elif operation == "/" :
    print("Sonuç :" + str(firstNumber / secondNumber))
