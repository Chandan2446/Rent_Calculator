
Rent=int(input("Enter the hostel rent:="))
person=int(input("Enter the total room-mates in your hostel:="))
Food=int(input("Enter the total price food order:="))
Electric_spend=int(input("Enter the total spend electric charge:="))
Electric_per_unit=int(input("Enter the electric unit in your area:="))
 
Total_electric_charge = Electric_spend*Electric_per_unit

Final_rent_calculate=(Rent+Food+Total_electric_charge)/person

print(Final_rent_calculate)
