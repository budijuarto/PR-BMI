# PR-BMI
print("Halo ini adalah BMI Calculator satuan kg dan meter")
tinggi = float(input("Silahkan masukan tinggi badan anda dalam meter : "))
berat  = int(input("Silahkan masukan berat badan anda dalam kg : "))
bmi = berat / (tinggi**2)

if bmi < 15:
     print("BMImu adalah ", bmi, "yang berarti Very severely underweight")
elif bmi >= 15 and bmi < 16:
    print("BMImu adalah ", bmi, "yang berarti severely underweight")
elif bmi >= 16 and bmi < 18.5:
    print("BMImu adalah ", bmi, "yang berarti underweight")
elif bmi >= 18.5 and bmi < 25:
    print("BMImu adalah ", bmi, "yang berarti normal")
elif bmi >= 25 and bmi < 30:
    print("BMImu adalah ", bmi, "yang berarti overweight")
elif bmi >= 30 and bmi < 35:
    print("BMImu adalah ", bmi, "yang berarti Moderately obese")
elif bmi >= 35 and bmi < 40:
    print("BMImu adalah ", bmi, "yang berarti Severely obese")
elif bmi >= 40:
     print("BMImu adalah ", bmi, "yang berarti 	Very severely obese")
