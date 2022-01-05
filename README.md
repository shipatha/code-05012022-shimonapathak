# code-05012022-shimonapathak

mass = int(input('mass: '))               #Enter your mass
height = float(input('Height: '))              #Enter your Height
bmi = mass/float(height**2)                #This is the calculator

print('BMI: '+str(bmi))                             #Print your BMI
if bmi <= 18.4:                                             #Condition if your bmi is less than 18.4
    print('Underweight')                             
elif  bmi>=18.5 and bmi<=24.9:                     #Condition if your bmi>=18.5 and bmi<=24.9
    print("Normal")
elif bmi >= 25 and bmi <=29.9:                     #Condition if you bmi >= 25 and bmi <=29.9
   print('Overweight')
elif bmi >= 30 and bmi <=34.9:                     #Condition if you bmi >= 30 and bmi <=34.9
   print('Moderately Obese')
elif bmi >= 35 and bmi <=39.9:                     #Condition if you bmi >= 35 and bmi <=39.9
   print('Severly Obese')
else:                                                         #Condition
   print('Very Severly Obese')
