# problems.python
'''1️⃣ Create and Access (Easy)

Create a dictionary to store details of a student:

name

age

grade

Print only the student's name.'''
#answer
student_detailes={
    "name":"arahan",
    "age":18,
    "grade": 10,
}
print(student_detailes["name"]) #op:arahan

'''2️⃣ Add a New Key

Create a dictionary:
car = {
    "brand": "Toyota",
    "model": "Camry"
}
Add a new key year = 2022 and print the dictionary'''
#answer
car = {
    "brand": "Toyota",
    "model": "Camry"
}
car["year"]=2022
print(car)


'''3️⃣ Update a Value

Given:
person = {
    "name": "Aman",
    "age": 25
}
Update the age to 26 and print the dictionary.'''
#answer
person = {
    "name": "Aman",
    "age": 25
}
person["age"]=26
print(person)
