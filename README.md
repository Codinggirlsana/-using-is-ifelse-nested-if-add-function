# -using-is-ifelse-nested-if-add-function

size=(input("enter the size of burger(s/m/l)?"))
bill=0
if(size =='s' or size =='s'):
    bill=100
    print("size of burger price is 100")
elif(size =='m' or size =='m'):
    bill=200
    print("size of burger price is 200")
else:
    bill=400
    print("size of burger price is 400")

add_tomato_sos=(input("add tomato sos(y/n)?"))
if add_tomato_sos=='y'or add_tomato_sos=='y':
    bill+=20
    print("the price of tomato sos is 20")
add_thumsup=(input("add thumsup (y/n)?"))
if add_thumsup=='y' or add_thumsup=='y':
    bill+=25
    print("the price of thumsup is 25")
print(f"total bill {bill}")
