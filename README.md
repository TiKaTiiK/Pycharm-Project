# Pycharm-Project
First Lesson
1. დაწერე პროგრამა რომელიც გეკითხება ჯერ სახელს, შემდეგ გვარს და ინფორმაციის მიღების
# შემდეგ ტერმინალში ბეჭდავს ერთმანეთის გვერდით.
# George Abramia
# 2. დაწერე პროგრამა რომელიც ითხოვს ორ რიცხვს, პირველი რიცხვი აჰყავს მეორის ხარისხში
# და შედეგი იბეჭდება ტერმინალში.
# 3. დაწერე პროგრამა რომელიც გეკითხება სახელს, გვარს, ასაკს და ქალაქს და ბეჭდავს
# ინფორმაციას შემდეგი სახით:
# Name: Lia
# Surname: Kebadze
# Age: 20
# City: Tbilisi
# 4. დაწერე პროგრამა, რომელიც გთხოვს შეიყვანო ნებისმიერი სამი სხვადასხვა ხილის
# დასახელება ცალცალკე. რეზულტატი კი იბეჭდება შემდეგი სახით:
# Apple//Peach%%Orange
# 5. დაწერე პროგრამა, რომელიც გთხოვს შეიყვანო ტექსტი, დათვლის მასში არსებული
# სიმბოლოების რაოდენობას და გამოიტანს შედეგს შემდეგნაირად:
# Number of symbols: 5

# 1.
a = input("What is your name? ")
b = input("What is your surname? ")
print(a, b)
print("Giorgi Abramia")

# 2.
a = 5
b = 2
print(a ** b)

# 3.
name = input("What is your name? ")
surname = input("What is your surname? ")
age = input("What is your age? ")
city = input("What is your city? ")

name1 = "Lia"
surname1 = "Kebadze"
age1 = "20"
city1 = "Tbilisi"

text = f"""
Name: {name1}
Surname: {surname1}
Age: {age1}
City: {city1}
"""
print(text)

# 4.1
a = input("Enter Fruit1 Name: ")
b = input("Enter Fruit2 Name: ")
c = input("Enter Fruit3 Name: ")

d = "Apple"
e = "Banana"
f = "Orange"
g = "//"
h = "%%"

text = """
{d}{g}{e}{h}{f}
""".format(d=d, g=g, e=e, h=h, f=f)
print(text)

# 4.2
a = 'Apple'
b = 'Banana'
c = 'Orange'
print(a, "//", b, "%%", c, sep="")

# 5.
a = input("Enter the text: ")
print(len(a))
