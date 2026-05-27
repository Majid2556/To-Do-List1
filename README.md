# To-Do-List1

tasks = []

while True:
    task = input("کار جدید: ")

    if task == "exit":
        break

    tasks.append(task)

print(tasks)
