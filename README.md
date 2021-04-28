# if-Statements

#conditional tests- testing for equalities
sanrio_1 = 'keroppi'
print("Is sanrio == 'keroppi'? I predict True.")
print(sanrio_1 == 'keroppi')

sanrio_2 = 'hello kitty'
print("Is sanrio == 'Hello Kitty'? I predict True.")
print(sanrio_2 == 'hello kitty')

sanrio_3 = 'pochacco'
print("Is sanrio == 'Pochacco'? I predict True.")
print(sanrio_3 == 'pochacco')

sanrio_4 = 'chococat'
print("Is sanrio == 'Chococat'? I predict True.")
print(sanrio_4 == 'chococat')

sanrio_5 = 'badtzmaru'
print("Is sanrio == 'Badtzmaru'? I predict True.")
print(sanrio_5 == 'badtzmaru')

sanrio_6 = 'cinnamoroll'
print("Is sanrio == 'Cinnamoroll'? I predict True.")
print(sanrio_6 == 'cinnamoroll')

sanrio_7 = 'gudetama'
print("Is sanrio == 'Gudetama'? I predict True.")
print(sanrio_7 == 'gudetama')

sanrio_8 = 'my melody'
print("Is sanrio == 'My Melody'? I predict True.")
print(sanrio_8 == 'my melody')

sanrio_9 = 'kuromi'
print("Is sanrio == 'Kuromi'? I predict True.")
print(sanrio_9 == 'kuromi')

sanrio_10 = 'pompompurin'
print("Is sanrio == 'Pompompurin'? I predict True.")
print(sanrio_10 == 'pompompurin')


#finding a false
print("Is sanrio == 'Mickey'? I predict False.")
print(sanrio_1 == 'mickey')

print("Is sanrio == 'Minnie'? I predict False.")
print(sanrio_2 == 'minnie')

print("Is sanrio == 'Goffy'? I predict False.")
print(sanrio_3 == 'goofy')

print("Is sanrio == 'Donald'? I predict False.")
print(sanrio_4 == 'donald')

print("Is sanrio == 'Dasiy'? I predict False.")
print(sanrio_5 == 'daisy')


#testing for inequality
sanrio_11 = 'aggretsuko'
if sanrio_11 != 'pluto':
    print("\nThat is not a Sanrio character")


#using the lower() method
print(sanrio_11 == 'Aggretsuko')
print(sanrio_11.lower() == 'aggretsuko')


#checking if an item is on a list
sanrio_friends = ['hello kitty', 'pochacco', 'keroppi']
friend = 'pickachu'
if friend not in sanrio_friends:
    print(f"\n{friend.title()} is not part of the Sanrio friends.")


#adult ages
my_age = 28
print(my_age == 28)
print(my_age < 50)
print(my_age > 75)
print(my_age <= 25)
print(my_age >= 15)


#if and else statements
alien_colors = ['green', 'blue', 'yellow']
if 'green' in alien_colors:
    print("\n5 points for the green alien!")
if 'blue' in alien_colors:
   print("10 points for a blue alien!")
if 'yellow' in alien_colors:
    print("15 points for the yellow alien!")
else:
    print("Looser!")

favorite_fruits = ['strawberries', 'bananas', 'watermelon']
if 'strawberries' in favorite_fruits:
    print("\nStrawberry feilds forever!")
if 'bananas' in favorite_fruits:
    print("\nThis ish is BANANAS!")
if 'watermelon' in favorite_fruits:
    print("\nWatermelon-Sugar-HIGH!")
else: 
    print("\nThat is not a musically based fruit.")

#if and elif statements with numbers
dinseyland_guest_age = 28
if dinseyland_guest_age < 2:
    print("\nBabies are free of admission")
elif dinseyland_guest_age < 4:
    print("\nToddlers are $25 for admission") 
elif dinseyland_guest_age < 13:
    print("\nChildren are $50 for admission")
elif dinseyland_guest_age < 20:
    print("\nTeens are $75 for admission")
elif dinseyland_guest_age < 65:
    print("\nAdults are $100 for admission")
elif dinseyland_guest_age < 66:
    print("\nSeniors are $50 for admission")
else:
    print("\nThe dead are not allowed.")

#if statements with lists
usernames = ['admin', 'assistant', 'supervisor']
for username in usernames:
    if username == 'admin':
        print("\nWelcome Admin. Would you like to see a status report?")
    else:
        print("\nHello, thank you for loggin in again.")

#empty if statements
logins = []
if logins:
    for login in logins:
        print(f"\nWe need to find some users")
    print("\nUser is here")
else:
    print("\nUser failed to login.")

#checking usernames- ensuring unique names within a list
current_users = ['user1', 'user2', 'user3', 'user4', 'user5']
new_users = ['new1', 'new2', 'user3', 'new4', 'new5']
for new_user in new_users:
    if new_user in current_users:
        print("\nSorry, that username is taken. Please try again.")
    elif new_users == 'New1':
        print("\nUsername cannot be accepted as is. Try again")
    elif new_users == 'New2':
        print("\nUsername cannot be accepted as is. Try again")
    elif new_users == 'New4':
        print("\nUsername cannot be accepted as is. Try again")
    elif new_users == 'New5':
        print("\nUsername cannot be accepted as is. Try again")
    else:
        print("\nThis username is avaliable.")
    
#ordinal numbers
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9]
for number in numbers:
    if number == 1:
        print("1st")
    elif number == 2:
        print("2nd")
    elif number == 3:
        print("3rd")
    elif number == 4:
        print("4th")
    elif number == 5:
        print("5th")
    elif number == 6:
        print("6th")
    elif number == 7:
        print("7th")
    elif number == 8:
        print("8th")
    elif number == 9:
        print("9th")
    else:
        print("ERROR")
