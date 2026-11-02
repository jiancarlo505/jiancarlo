print("          |==================================|             ")
print("          |----- INTRODUCTION IN PYTHON -----|             ")
print("          |==================================|             ")
print("")
print(" |----[PRELIM]----| |----[MIDTERM]----| |----[FINALS]----|")
print("")
print("_|_______________________________________________________|_")
print(" |                  AVAILABLE LESSON                     |")
print(" | PYTHON LESSON:                                        |")
print(" | [1]  Python syntax                                    |")
print(" | [2]  Python output                                    |")
print(" | [3]  Python comments                                  |")
print(" | [4]  Python variables                                 |")
print(" | [5]  Python strings                                   |")
print(" | [6]  Python booleans                                  |")
print("_|_______________________________________________________|_")
print(" |                                                       | ")
print("")

name = input("you can enter your name: ")
age = int(input("you can your age: "))
birthday = int(input("you can enter your birthday: "))
address = input("you can enter your address: ")
print("")

code = input("enter Python lesson: ").upper()

if code == "1":
    lesson = "python syntax"
    print(lesson)
elif code == "2":
    lesson = "python output"
    print(lesson)
elif code == "3":
    lesson = "python comments"
    print(lesson)
elif code == "4":
    lesson = "python variables"
    print(lesson)
elif code == "5":
    lesson = "python strings"
    print(lesson)
elif code == "6":
    lesson = "python booleans"
    print(lesson)
else:
    print("invalid code!!!")
    exit()
qty = int(input("enter python lesson: "))

