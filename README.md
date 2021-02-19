
## even= /2
## odd!= /2
print('welcome in the even-odd game')
print('Please enter a number... And i will tell you if it odd or even')
print('if you wanna close the game enter x')
while True:
    number=input('Enter a number:')
    if number=='x':
        print('closing the game')
        print('thanks ... ')
        break
    try:
        number=int(number)
        if number % 2 == 0:
            print("Even number")
        else:
            print("Odd number")
    except ValueError:
        print("Please enter a valid number")
        print("---------------------------")
