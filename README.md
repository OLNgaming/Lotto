# Lotto

import random

print("Lotto")
print("")

wiederholen = int(input("Wie viele Lottoscheine: "))

for i in range(wiederholen):
    a = [random.randint(1, 50) for i in range(5)]
    print(a)

print("")
zusatz = int(input("Wie viele zusazzahlen": ))
