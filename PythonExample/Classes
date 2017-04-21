import datetime # we will use this for date objects
#Defining a class
class Person:
    #Defining a class
    def __init__(self, name, surname, birthdate, address, telephone, email):
        # type: (object, object, object, object, object, object) -> object
        self.name = name
        self.surname = surname
        self.birthdate = birthdate

        self.address = address
        self.telephone = telephone
        self.email = email

    def age(self):
        today = datetime.date.today()
        age = today.year - self.birthdate.year

        if today < datetime.date(today.year, self.birthdate.month, self.birthdate.day):
            age -= 1

        return age

person = Person(
    "Maria",
    "Sanchez",
    datetime.date(1993, 1, 26), # year, month, day
    "No. 12 Short Street, Greenville",
    "555 456 0987",
    "maria@example.com"
)

print(person.name)
print(person.email)
print(person.age())
