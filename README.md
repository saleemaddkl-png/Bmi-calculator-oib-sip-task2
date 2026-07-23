print("===== BMI Calculator =====")

name = input("Enter Your Name: ")
age = int(input("Enter Age: "))
weight = float(input("Enter Weight (kg): "))
height = float(input("Enter Height (m): "))

bmi = weight / (height ** 2)

print("\n------ Result ------")
print("Name:", name)
print("Age:", age)
print("BMI:", round(bmi, 2))

if bmi < 18.5:
    print("Status: Underweight")
elif bmi < 25:
    print("Status: Normal Weight")
elif bmi < 30:
    print("Status: Overweight")
else:
    print("Status: Obese") 
    #Bmi-calculator-oib-sip-task2
    #output
    ===== BMI Calculator =====

Enter Your Name: Saleema 
Enter Age: 20
Enter Weight (kg): 55
Enter Height (m): 1.60

------ Result ------
Name: Saleema
Age: 20
BMI: 21.48
Status: Normal Weight
