print("===== MINI GROCERY STORE =====")
print("Enter quantity of each item:")

rice = int(input("Rice (Rs.60/kg): "))
milk = int(input("Milk (Rs.30/litre): "))
bread = int(input("Bread (Rs.40/packet): "))
sugar = int(input("Sugar (Rs.45/kg): "))
oil = int(input("Cooking Oil (Rs.120/litre): "))
eggs = int(input("Eggs (Rs.7/piece): "))
biscuits = int(input("Biscuits (Rs.10/packet): "))
tea = int(input("Tea Powder (Rs.50/packet): "))
soap = int(input("Soap (Rs.35/piece): "))
noodles = int(input("Noodles (Rs.15/packet): "))

quantities = [rice, milk, bread, sugar, oil,
              eggs, biscuits, tea, soap, noodles]

if any(q < 0 for q in quantities):
    print("Quantity cannot be negative. Please try again.")

else:
    rice_amount = rice * 60
    milk_amount = milk * 30
    bread_amount = bread * 40
    sugar_amount = sugar * 45
    oil_amount = oil * 120
    eggs_amount = eggs * 7
    biscuits_amount = biscuits * 10
    tea_amount = tea * 50
    soap_amount = soap * 35
    noodles_amount = noodles * 15

    total = (rice_amount + milk_amount + bread_amount +
             sugar_amount + oil_amount + eggs_amount +
             biscuits_amount + tea_amount + soap_amount +
             noodles_amount)

    print("\n===== CUSTOMER BILL =====")
    print("Rice: Rs.", rice_amount)
    print("Milk: Rs.", milk_amount)
    print("Bread: Rs.", bread_amount)
    print("Sugar: Rs.", sugar_amount)
    print("Cooking Oil: Rs.", oil_amount)
    print("Eggs: Rs.", eggs_amount)
    print("Biscuits: Rs.", biscuits_amount)
    print("Tea Powder: Rs.", tea_amount)
    print("Soap: Rs.", soap_amount)
    print("Noodles: Rs.", noodles_amount)
    print("-------------------------")
    print("Total Bill: Rs.", format(total, ".2f"))
    
