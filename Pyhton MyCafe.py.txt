print("Hello, welcome to Fahim Coffee!!!!!!!!!!!")

name = input("What is your name?\n")

if name=="Ben":
    print("You're not welcome here evil ben!! Get out!!")
else:
    print("Hello " + name+", thank you so much for coming in today.\n\n\n")

menu = "Black Coffee\nEspresso\nLatte\nCappuccino\n"

print(name + ", what would you like from our menu today? Here is what we are serving.\n" + menu)

order = input()

price = Espresso = 1.99
if order == "Latte":
    price = 2.99
else:
    order == "Black Coffee"
    price = 0.99
if order == "Cappuccino":
    price = 3.99

print("Sounds good " + name + ", we'll have that " + order + " ready for you in a moment...")

print("How many " + order + " would you like?")

quantity = input("How many wouyld you like?\n")

total = price * int(quantity)

print("Thank you. Your total is : $" + str(total))

print("Have a lovely day!")

print("Would you like anything else?")
if order == "No":
    print("Thank you and come again")
elif order == "Yes":
    print("What else would you like?")
    print(name + ", what would you like from our menu today? Here is what we are serving.\n" + menu)
    order = input()
