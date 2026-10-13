studentName = str(input("Name: "))
studentAge = int(input("Age: "))

subjectsTaking = int(input("How many subjects taking: "))

subjectsList = []
for i in range(1, subjectsTaking + 1):
  subjectsName = str(input("Subject Name: "))
  subjectsList.append(subjectsName)

print("List of Subjects: ")
for index, subjectsName in enumerate(subjectsList):
  print(f"{index + 1}: {subjectsName}")  

