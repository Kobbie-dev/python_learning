# Swoove Delivery Calculator App
# With a nicely printed receipt

print("Welcome to Swoove Package Deliveries")
print("This is an interactive service that makes delivering of packages very easy and incredibly fast")
print("How may we help you today😊")
print("Please enter accurate details below for accurate pricing and stress free deliveries")
name = (input("What is your name?"))
location_1 = (input("What is the current location of the package/s?"))
location_2 = (input("Where is the package/s going to?"))
weight = float(input("What is the weight of the package/s in KG?"))
distance = float(input(f"What is the approximate distance of travel in KM between {location_1} and {location_2}?"))
name_2 = (input("What is the name of the recipient of package/s?"))
no_of_recipient = (input(f"What is the phone number of {name_2}?"))
info = (input("Any additional information for driver?"))
print("Calculating total cost of Delivery")
total_1 = 20 + (weight * 1) + (distance * 2)
total_2 = total_1 * 0.15
total_3 = total_1 + total_2
print("The Total Receipt")
print(f"Customer's name:{name}")
print(f"Recipient's name:{name_2}")
print(f"Weight of Package/s:{weight}KG")
print(f"Distance of delivery:{distance}KM")
print(f"The total before VAT:GHC{total_1}")
print(f"VAT of 15%:GHC{total_2}")
print(f"TOTAL COST:GHC{total_3}")
print("Please note that there is a fixed charge of GHC20 not based on distance of delivery")
print("Thank you")
print("For any querries or concerns please don't hesitate to reach out to us on our e-mail down below")





              
