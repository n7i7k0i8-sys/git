balance  = 1000

print("welcome to ATM")
pin = input("enter pin:")
if pin=="1234":
    print("\n1. balance:")
    print("2. dospit:")
    print("3. withdraw:")
choice =int(input("enter choice:"))

if choice == 1:
        print("balance =",balance)

elif choice ==2:
amount =  float("input("deposit amount:"))
            balance +=amount
            print("updated balanace =",balance)

        elif choice ==3:
            amount = float ("input ("withdraw amount:"))
            if amount<= balance:
                balance -=amount
                print("updated balance =",balance)
                else:
                    print("insufficient balance")
                else:
                    print("invalid pin")
