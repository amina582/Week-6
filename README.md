vartable = "Özellikle balistik füzeler, seyir füzeleri ve düşman uçaklarını havada imha"
v1 = "Özellikle balistik füzeler, seyir füzeleri ve düşman"

variable2 = vartable.split(" ")

counter = 0

for vord in variable2:
    for char in vord:
        print(char)

    counter += 1
    print(counter)



from itertools import count

variable = "Özellikle balistik füzeler, seyir füzeleri ve düşman uçaklarını havada imha"
v1 = "Özellikle balistik füzeler, seyir füzeleri ve düşman"

variable2 = variable.split(" ")

counter = 0

for vord in variable2:
    for char in vord:
        print(char)

    counter += 1
    print(counter)



class Calculator:

    def __init__(self, a, b):
        self.num1 = a
        self.num2 = b

    def sum(self):
        result = self.num1 + self.num2
        print(result)

    def multiple(self):
        result = self.num1 * self.num2
        print(result)



class Me:

    def __init__(self, name="", age=0, gender=""):
        self.name = name
        self.gender = gender
        self.age = age
        self.classroom = []

    def show_my_cw(self):
        print("My name is {} and I am {} years old".format(self.name, self.age))

    def add_student(self):
        self.classroom.append(self.name)

    def show_classroom(self):
        for student in self.classroom:
            print(student)



calc = Calculator(5, 3)
calc.sum()
calc.multiple()

B = Me(name="Amneh", age=19, gender="female")
B.show_my_cw()
B.add_student()
B.show_classroom()
