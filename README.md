# project-euler-problems

def find_answer(m):
    y = 0
    for i in range(m):
        if i%3==0  or i%5==0:
            y+=i

    print(y)

find_answer(1000)
