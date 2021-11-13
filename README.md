# Body Mass Index (BMI) calculator
"""

     Body Mass Index (BMI) calculator :


"""


w = float(input('weight in kilo :'))    #For Example: 69 kilo
h = float(input('height in meter :'))   #For Example: 1.75 meter
bmi = w/h**2

if bmi < 15 :
    k = 'Very Severely Underweight'
elif 15 <= bmi <= 16 :
    k = 'Severely Underweight'
elif 16 < bmi <= 18.5 :
    k = 'Underweight'
elif 18.5 < bmi <= 25 :
    k = 'Normal'
elif 25 < bmi <= 30 :
    k ='Overweight'
elif 30 < bmi <= 35 :
    k = 'Moderately Obese'
elif 35 < bmi <= 40 :
    k = 'Severely Obese'
elif bmi > 40 :
    k = 'Very Severely Obese !!! '
    
    
print('Your Body Mass Index Is = ' + str(bmi) +' '+'And You Are'+' ' + k +' .')

