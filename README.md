# projectT1
printing all numbers from 0 to 100,skip values divisible by 5,3
printing all numbers from 0 to 100 which are divisible by 5 & 3

print()
#print all value from 0 to 100,skip values divisible by 5,3
i = 1
while i <= 100:
    if i%3 and i%5 != 0:
        print(i)
    i = i + 1
#print all numbers from 1 to 100 except the numbers divisible by 3 & 5

#******************-----------MODIFIED-----------***************************

i = 1
test = []
while i <= 100:
    if i%3 and i%5 != 0:
        test.append(i)
    i = i + 1
print(test)
#[1, 2, 4, 7, 8, 11, 13, 14, 16, 17, 19, 22, 23, 26, 28, 29, 31, 32, 34, 37, 38, 41, 43, 44, 46, 47, 49, 52, 53, 56, 58, 59, 61, 62, 64, 67, 68, 71, 73, 74, 76, 77, 79, 82, 83, 86, 88, 89, 91, 92, 94, 97, 98]
