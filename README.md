# NameProgramMUD
MUD Attempt
# this program says hello and asks for my name.

print('Greetings Stranger!')
print('What do your people call you?') # ask for their name
myName = input()
print('We meet at last, ' + myName)
print('The length of your name is: ')
print(len(myName))
print('How many years have you?') # ask for their age
myAge = input()
print('You shall be ' + str(int(myAge) + 1) + ' in a year.')
