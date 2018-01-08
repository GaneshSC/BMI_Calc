Weight_po = input("What is your weight in pounds?: ")
Weight_kg = int(Weight_po) * 0.453592

print("Your weight in kilograms is:",Weight_kg)

Height_In = input("What is your height in inches?: ")
Height_Meter = int(Height_In) * 0.0254

print("Your height in meters is:",Height_Meter)

BMI = float(Weight_kg / Height_Meter ** 2)
print("With these measurements of your body, we could conclude that your BMI is:",BMI)

if BMI < 18.5:
    print("You're underweight.")
elif BMI == 18.5 or BMI < 24.9:
    print("You have normal weight.")

if BMI == 30 or BMI > 30:
    print("You are obese.")
